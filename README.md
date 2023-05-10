# YouTube Historical Trendiness Dashboard

A Tableau dashboard that monitors historical data of YouTube videos "trendiness" throughout time.

###### ***![An image of the initial screen view of the Tableau dashboard](/images/Whole-DBoard_Upd.png)***

## Table of contents
- [General description](#general-description)<br>
    - [A Practicum DA project](#the-project-was-made-as-part-of-practicums-data-analytics-program)<br>
- [Used Technology](#used-technology)<br>
- [Features & Plots](#features--plots)
    - [The Trending History charts (Absolute & Relative)](#1-the-trending-history-charts-absolute--relative)
    - [The Trending Vids by Country chart](#2-the-trending-vids-by-country-chart)
    - [The Trending by Country & Category highlight table](#3-the-trending-by-country--category-highlight-table)


---
## **General description:**
The project's goal is to level-up marketing by analyzing trending videos on YouTube in order to determine what content deserves marketing attention, based on the video content's genre, popularity in different regions, and more.

###### ***The project was made as part of Practicum's Data Analytics program.***


###### [⭱ Back to Top](#youtube-historical-trendiness-dashboard)

---
## Used Technology:
**Tableau Public Version:** 2023.1 <br>

###### [⭱ Back to Top](#youtube-historical-trendiness-dashboard)

---
## Features & Plots:
The dashboard contains 4 charts which visualize the YouTube Trendiness data:
<details>
    <summary><h4>1. <i>The <code>Trending History</code> charts (Absolute & Relative)</i></h4></summary>
    <div style="padding-top: 10;">
        <code>Trending History</code> & <code>Trending History (%)</code> are both stacked-area charts which represent the historical change in trendiness of YouTube videos from various categories throughout time.<br>
        <i>However</i>, the latter shows the data as relative values, i.e. each genre's controlled percentage out of the total amount of videos published in YouTube on each day during the recorded timespan.<br>
        <b><i>Optionable Filters:</i></b> Date, Selected countries, Selected categories.<br><br>
        <img src='/images/Historical-Trendines-Charts.png' alt='Screenshot of both the `Trending History` charts'>
</details>

<details>
    <summary><h4>2. <i>The <code>Trending Vids by Country</code> chart</i></h4></summary>
    <div style="padding-top: 10;">
        <code>Trending Vids by Country</code> is a pie chart which displays the shares of the different regions' published videos to YouTube.<br>
        <b><i>Optionable Filters:</i></b> Date, Selected countries, Selected categories.<br><br>
        <img src='/images/Pie-Chart_Vids-By-Country.png' alt='Screenshot of the `Trending Vids by Country` pie chart' width=500 height=479.4 align='center'>
</details>

<details>
    <summary><h4>3. <i>The <code>Trending by Country & Category</code> highlight table</i></h4></summary>
    <div style="padding-top: 10;">
        <code>Trending by Country & Category</code> is a highlight table visualization which displays the shares of the different regions' published videos from the total videos a specific genre has in YouTube.<br>
        By default it displays the absolute numbers, yet you can use the <code><i>Show Values As</i></code> filter to toggle into relative values presented as floats.<br>
        <b><i>Optionable Filters:</i></b> Date, Selected countries, Selected categories, Show Values As (Absolute/Relative).<br><br>
        <img src='/images/HLTable_Trending-by-Country%26Category.png' alt='Screenshot of the `Trending Vids by Country` pie chart' width=629 height=418.5 align='center'>
</details><br>
    
###### [⭱ Back to Top](#youtube-historical-trendiness-dashboard)
