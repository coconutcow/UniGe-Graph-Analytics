# GraphAnalytics: Assignment Two

## Brace, breath, and begin

#### Objective:
Investigate the robustness of networks, and implement some changes on your network to visualize, and assess, the magnanimity of attacks on connected networks. 

#### Programming Language:
Python, compiled using Jupyter Notebook

#### Libraries used:
* NetworkX
* Pandas
* MatplotLib
* Numpy
* Random
* Urllib.request

#### Data Source:
[OpenFlights](https://openflights.org/data.html "OpenFlights")

<br>I have used a library named 'urllib.request' in order to extract the file straight from the url thus making this project light, quick, and more efficient to execute.

## The Dataset

RyanAir, Lufthansa, American Airlines, Qatar ?
These are all popular names that are discussed from time to time, and form an integral part of this globalized world.
Airports, Airlines, and Routs, can all play important roles in deciding which country do we go to next. This is an initiative to plot the airports, airlines, and their consequent routes on a global map. The dataset has been keenly observed, and for my purpose has been tailored using python to satisfy the intent. Additionally, the modifications have been made in order to provide the best form of representation of the idea behind this implementation.
There is no need for you to download the dataset. 

## Wanderlust or Wander-lost

Implementing the code gives us interesting results.
The red dots represent the airports, and the black lines represent the routes between two airports.

### Part One
#### We initially try and understand the specifics of what happens when networks lose nodes or edges. The effects are understood with the below two graphs

#### Below is a fully connected graph of 20 nodes
<br>![Graph Image 1](https://lh3.googleusercontent.com/SLgqqgDjVjqox59GUV5SievuXlcInvKLM-L2pxRrBMaSYINCyYQUVFELYSgg7txOUReetNEVgMFsNL-S0Lkq9xQg11jylrdfIFbynfFd7y-felesU9gDcyFfnvzBhr05kSKhxIVpXF5Tua7_D14kHRLw40si57GNiO6XXLhYOQFR263JiSfnSzmEcMWgIYdaijpSEpaa8ZKkLOjekFI2u81XijE26th4jrFddrN9o8PiYyfIX2efVOHzeKMqQ1eeBhI2hV44ezB7pFnPbMTEOEcHjv00wCWpnw8jE_3YOCKGfZ5JhFGGTj_QWUrDLGDuMkRNnCbWUYb6Ouxtoqj1X8DPTXCdTfnwUcMiGHlO_0jhZQ_ysVqaP8GdPuGhimpV6Tj_scUkEq1TgWmpP-ixcUyAmuspco5b5oBqI2JGhyhngUw-mmCXUM22-AjqQVXPYcOi0PtMcGoNmaufks4234_PnS1hF5yOem41JNXO8QlyaH5SPwXFlS0nHS_X_dQ6oklY3UmDMmquHBdyHPO41_PDZsJxALNeD-2ORU_xbV3TO4Fz0D7w5p_zi8zVftopHAdm8YWJ8fOpb63LNFDTEqPRsqowdDMGa8uWVtRHQldTgsA6aLnsoCzZgPICoBq4jSdXXes0IndYEBErEtoZvAW2ju9fuA=w484-h319-no)
##### Graph Metrics: Before the attack

<table class="tg" >
  <tr>
    <th class="tg-yw4l" align="left"><b>Diameter of Network</b></th>
    <th class="tg-yw4l" >1</b></th>
  </tr>
  <tr>
    <td class="tg-yw4l"><b>Degree Centrality of Node 0</b></td>
    <td class="tg-yw4l">1</td>
  </tr>
  <tr>
    <td class="tg-yw4l"><b>Clustering Coefficient of Node 0</td>
    <td class="tg-yw4l">1</td>
  </tr>
</table>

#### What happens when we drop some edges and nodes?
<br>![Graph Image 2](https://lh3.googleusercontent.com/jdgXbocrTFWzn8amtnUAl3JiOZ3r7qD5HJN2DTbJeIZKMkaoQnITTyt_Xz1pY-ZAtMteqK-gKbZxf7qAHcrrCN8oxv-7Kxxeq029UQ3SGdSVd8NGokeVV0gz1l-soqsRLx0L7CThweXr63fW1XTazAsoPvpIfuqK1H_XWmhr_nnO1LMdFd80cbcY18aKKdtYsswmGNAHmo--UuzJlpnhLXkw7B64XMEd9zhQQtRudxtqMIpm9duOQv70Sm97DC7fP-IZAAzoZT5y7w6bHioN6MWzdxqd1uYrKpMUGMeU3Kc6_DLxE1J5zQxGKEiMpH_UbB_QDIS7cwj0m69XHtoyGnNLC4N0GSEK_L7oZmHMzKoICeVffLnhEmhsFNlVUHsWEAnWUKi4H2A__kEheOLTPaff0QgP8k4WBf4IOjKGydiQlaOE4B3rCC0JIlMrCi0lqVwVOpIE1Qgk2UGhHfrxiLbSJziH36I-JrCyQkocfGvfc1DH2kPgslX21Xg5PDvturgYD5conoMLP-VpM_8slgKJBjzng9c11h3RmpIYIlH5YdieVBu1Vtfx5tEC3lGhViy6qA36bvW9lr9mO4jtg2tvmypNRwWpwBhln7oihUX_vnOTGDdVo7iRL2SPOb2KFBdjkSAeFtW__z7xLokYLTaWf406OA=w484-h319-no)
##### Graph Metrics: After the attack
<table class="tg">
  <tr>
    <th class="tg-yw4l" align="left"><b>Diameter of Network</b></th>
    <th class="tg-yw4l">2</b></th>
  </tr>
  <tr>
    <td class="tg-yw4l"><b>Degree Centrality of Node 0</b></td>
    <td class="tg-yw4l">0.43</td>
  </tr>
  <tr>
    <td class="tg-yw4l"><b>Clustering Coefficient of Node 0</td>
    <td class="tg-yw4l">0.93</td>
  </tr>
</table>

### Part Two
#### How would dropping nodes affect our communication between countries, consequently the people living in those countries ? The visualized results tend to show us how important it is to remain connected, and how different would the world look like losing communication points.

<br>![Graph Image 3](https://lh3.googleusercontent.com/HmDdJvWYo1fmmad-Me-1-lHAmzG5mhcCfWqKCllxxFN9099yI6farUaTegnF0bCUZ-zCRW2UU6sIlpXKizaPMBb8c-3aGaWHHf_Kxfcf8Mb3RsRglOrzxDDIaCmmm4d47P8eLkkljYpTSnrDyohrTVXyCJTGHkhh6A9YufsSTnErylF8ZJfw8j3aqtS1UMT1gZ9_r9jTxcJVYKRxxlCEjJj3OOlLY8Q6bCTqagrGTKJLfjEuaCQdLxBKrXonkYOXgj7eJeASCC0z65jvULhJHA87U8PGnN0UJPEdr4QNR17VRD-yjixqJ670nZkgYY_GqKUSsS2iOFtphoV_li6QDNu2t1m0XKo_iLaOStjIkg07Y4Ljoo3op6hI7_XjoNt3iMWD_QBEtH6JhPvhFtHDCU1LhRPLx5yDR764yyBwyH5ZhfxQMjlGfGB9j5NTNeMjWEUK5wmyqAqWeLIwh6t_GztLZscvo4vrO22zIH4cWRj4LXx37Q7jTOym-cDzt8kwgNkIUh_j1QeFJpjyxXvz7_NNY2FK7rFI1fOshDLxsdYcbS3IqioK8XbKxp9t3ntatM4QRDx_pntG_aruo5VzWeiwLwRY_oQEcDh_njBUR1qJkwgq3iOJVeTOA_pSrPkAHWWdBaKjeHK_Dk_p9crm1HBPJfVJ4w=w474-h319-no)
<br>![Graph Image 4](https://lh3.googleusercontent.com/-GoBq5jN3NRQUvlj3LH_tm2GEr7rMrj6JzDqQLwqd4PKlTrC1xDJ8a9J-LJBjsbmJNm0vFivfbIwTBCqpoBmSj9S4k0hBugBtfDJv7yLajI33wRJfP2kY1qZGfGV9cUUg48Ynw87gJoULgWV0I3pK5NoXLyFxDdnJ-GoGUsQa3fwZUnBraTVi5ZhN69hshpg88z84LPkzpHQXWK22tCEVbiOHY-ajSyvy1qpwxjsbWp_zAUHlgI5GDVKW_4EmGGtCdGdpn40ii0yihfYT2MYyrKSAAAihIROFkQp2LIP-UMXPKx3-DKl9b2s8IwYqLBq0-axQSJhhNVF2JBaq1xdz2zf8l_6LoZQ6HE7uJE6l6MsDsUZl3WRPILhx6JDOYrt9pqzf3hmc0RmlxKzE4xfDD2RsYSmaA36NTsYkQjf6HWdRmFJ_aOH32YSl0ZoYGAn_Y7Gtr3gk1qGj_LwYie96BhBmrxTKczL1SPdzqot4oNbJUwPtIuVmtn_pGDmtEHBMiKXsLLjCoBrX_qBkZ9W4hoQiaRtOT_sizgRcOYtqovk94IWNOHOim0qPP8zgD8GEpq-IBffxvExCWel8P8F1p8SQphkL5sYl8hn71x5Amyr7sG9tGo47oikBgBUFeXDa4YcV9ULXb-REgYaUXmPVDuR0wxa5A=w1018-h745-no)
