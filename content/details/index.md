---
title: "meeting details"
subtitle: ""
date: 2022-08-30T05:10:00-04:00
draft: false
author: ""
authorLink: ""
description: "meeting details"
license: ""
images: ["/featured-meeting-1.jpg"]

tags: []
categories: []

featuredImage: "featured-meeting-1.jpg"
#featuredImagePreview: ""


---




{{< meeting_list >}}

{{< echarts >}}
option = {
  xAxis: {
    data: ['A', 'B', 'C', 'D', 'E']
  },
  yAxis: {},
  series: [
    {
      data: [10, 22, 28, 23, 19],
      type: 'line',
      lineStyle: {
        normal: {
          color: 'purple',
          width: 4,
          type: 'dashed'
        }
      }
    }
  ]
};
{{< /echarts >}}
