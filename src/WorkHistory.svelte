<script>
    import Layout from './shared/Layout.svelte'
    import Timeline from './shared/Timeline.svelte'

    let workTimeline = [
        {year: '2015', details: [
                        {title: 'Sigma infosolutions Pvt. Limited', monthStamp: 'Jun'}
                        ]
        },
        {year: '2018', details: [
                        {title: 'Infrrd.ai Pvt. Limited (current)', monthStamp: 'Apr'}
                        ]
        },
        ]
</script>


<Layout gradientBg={true} hostComponent={'workHistory'}>
    <Timeline showMonthStamp={true} timelineEntries={workTimeline}></Timeline>
</Layout>