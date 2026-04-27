---
# Do not edit the text between these lines!
layout: default
---

# EX09 Data Analysis Project

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="/ex09-project/static/imgs/logo.png" alt="Image of Comp110 rainbow logo" width="500">

## Summary

This project works to analyze student interest in livestreamed and recorded lectures using survey data from COMP110. The goal is to determine whether adding livestream or recorded lecture options is something that is wanted by the students and whether it would improve student learning and accessibility.

## Visualizations
These visualizations show how student responses are distributed, how key data content relates to each other, and how responses vary across the different categories.

<img src="/ex09-project/static/imgs/chart1.png" width="500">
<img src="/ex09-project/static/imgs/chart2.png" width="500">
<img src="/ex09-project/static/imgs/chart3.png" width="500">

## Analysis

The histogram shows that most students rated their interest in livestreamed lectures quite high, with responses concentrated around the 6 and 7 mark. This emphasizes that there is a strong overall demand for livestream or recorded lecture options among the students that are enrolled in the class.

The relationship between lecture effectiveness and livestream interest also shows a positive correlation. This means that students who find lectures more effective are also more likely to support livestreaming. As a result, this suggests that livestreaming would increase the value of lectures rather than replacing it.

The boxplot further supports this by showing that the median values for livestream interest and pre-lecture videos are very high, indicating that there is consistent student preference for additional access to lecture content across the entire dataset.

## Conclusion

The data support the idea that adding livestreamed or recorded lectures would create value for students. The frequency counts show that the highest number of responses for "add_livestreams" is 7, with 301 responses, followed by 6 with 145 responses. This suggests a strong overall preference for livestream options. This pattern is also visible in the histogram, where responses are heavily concentrated on the higher end of the scale. 

The relationship plot between "ls_effective" and "add_livestream" shows a clear upward trend, meaning that as students rate the lecture as more effective, their interest in livestreaming also increases. This suggests that livestreaming is not replacing the value of lectures, but rather reinforcing it for students who already find lectures helpful. 

The boxplot further supports this conclusion by showing that the median values for all three variables are relatively high, with "add_livestream" and "pre_lecture_videos" centered around 6, and "ls_effective" slightly lower but still above average. This confirms that students generally view lectures as effective and simply want additional access to lecture content in the form of a video.

Based on this analysis, implementing livestreamed recorded lectures would likely improve accessibility and create a better learning environment. A refinement of this idea would be to provide both live access and recorded playback so students can review content later. However, there can be negatives to this. Livestreaming may reduce in-person attendance and classroom interaction, which could negatively impact student engagement. It may also require additional effort from the staff and lecturers to manage recordings and maintain the quality of content. Some students may also rely too heavily on recordings instead of attending lectures. 

All in all, the data shows strong student demand for livestreamed or recorded lectures, which makes this a valuable improvement, but it should be implemented alongside other strategies to maintain student engagement.


## Recommendations

The course should implement livestreamed and recorded lectures, but it should be implemented alongside other strategies to maintain student engagement.