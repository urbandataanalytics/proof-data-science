# Data Science. Proof of knowledge  

## Context
This dataset is a record of real estate transaction prices in Japan from 2005 to 2019, surveyed by the MLIT(Ministry of Land, Infrastructure, Transport and Tourism of Japan). Dataset contains real estate transaction prices for 47 prefectures in Japan.

## FILE HERE
https://drive.google.com/file/d/144JpUmqlLZ4-z-EQxngSAWB4WYoaZ6kj/view?usp=sharing

## Principal Data Fields

|FieldName| Description | Values |
|--|--|--|
| Type | Real Estate Type | Residential Land(Land Only) , Agricultural Land , Residential Land(Land and Building) , Pre-owned Condominiums, etc. , Forest Land |
| Region | The characteristics of surrounding areas | Residential Area, Potential Residential Area, Commercial Area, Industrial Area |
| MunicipalityCode | City code of japan |  |
| Prefecture | Prefecture Name of japan |  |
| TimeToNearestStation | Time to the nearest station (original). The original data contains non-numeric values(ex. 1H-1H30, 30-60minuts). It is difficult to use for data analysis, I added min/max time to nearrest station columns. |  |
| TradePrice | Trade prices (Yen) |  |
| FloorPlan | Floor plan | 3LDK' '4DK' '2LDK' '4LDK' '2DK' '1K' '3LDK+S' '5LDK' '3DK' '1LDK' '2DK+S' 'Open Floor' '1DK' '1R' '4LDK+S' '2K' '2LDK+S' '6DK' '1LDK+S' '5DK' '1R+S' '1LK' '1K+S' '3K' '7LDK' '4K' '3DK+S' '3D' '1DK+S' '6LDK' 'Studio Apartment' '6LDK+S' '4L+K' '5LDK+S' '7DK' '3LK' '5K' '2K+S' '8LDK' '3LDK+K' '3LD' '1L' '4DK+S' '2LK' 'Duplex' '7LDK+S' '4LDK+K' '3LD+S' '2LD+S' '8LDK+S' '4L' '2L' '2LDK+K' '2LK+S' '5LDK+K' '1LD+S' '2L+S' '3K+S' '1DK+K' '2LD' '1L+S' '2D' '4D' |
| Areas | The surveyed area (m^2) |  |
| AreaIsGreaterFlag | An area of 2000 m^2 or greater, the area data are displayed 2000, and this flag is true. |  |
| UnitPrice | Unit Land Price(Yen) per m^2 |  |
| PricePerTsubo | Unit Land Price(Yen) per Tsubo. Tsubo is a japanese units, see [https://en.wikipedia.org/wiki/Pyeong#Tsubo](https://en.wikipedia.org/wiki/Pyeong#Tsubo) |  |
| LandShape | Land Shape | Semi-rectangular Shaped' 'Semi-trapezoidal Shaped' 'Irregular Shaped' 'Trapezoidal Shaped' 'Rectangular Shaped' 'Semi-shaped' 'Semi-square Shaped' 'Square Shaped' 'Flag-shaped etc.' |
| TotalFloorArea | Total Floor Area (m^2). |  |
| BuildingYear | Construction Year of Building |  |
| Structure | Building Structure. SRC= Steel frame reinforced concrete, RC= Reinforced concrete, S = Steel frame, LS = Light steel structure, B = Concrete block, W = Wooden | RC' 'W' 'SRC' 'S' 'LS' 'S, W, LS' 'B' 'W, LS' 'RC, W' 'S, W' 'RC, S' 'W, B' 'RC, LS' 'RC, W, LS' 'RC, W, B' 'RC, S, LS' 'SRC, W' 'S, B' 'SRC, RC' 'S, LS' 'S, W, B' 'B, LS' 'RC, B' 'SRC, S' 'RC, S, W' 'SRC, B' 'W, B, LS' 'S, B, LS' 'RC, B, LS' 'RC, S, B' 'SRC, RC, S' 'SRC, LS' 'SRC, W, B' 'S, RC, W' 'RC, S, W, B' |
| Use | Current Usage. For example, House, office, shop, factory, warehouse, workshop, parking lot, and other |  |
| Purpose | The purpose of future use. For example, House, shop, office, factory, warehouse, and other. | Other' 'House' 'Warehouse' 'Office' 'Factory' 'Shop' |
| Classification | Frontage road Classification | Road' 'City Road' 'Prefectural Road' nan 'Village Road' 'Private Road' 'National Highway' 'Access Road' 'Agricultural Road' 'Ward Road' 'Town Road' 'Kyoto/ Osaka Prefectural Road' 'Forest Road' 'Hokkaido Prefectural Road' 'Tokyo Metropolitan Road' |
| Period | Time of transaction |  |
| Year | Time of transaction year |  |
| Quarter | Time of transaction year-quarter |  |
| Renovation | renovation? | Not yet 'Done' |
| Remarks | Note |  |


## Questions & Inspiration

- Has the price of real estate in Japan increased/decreased in the last 10 years? (residential use)
- Is there a price difference between Tokyo(Capital of Japan) and local areas?
- Are there any duplicates?
- Develop an algorithm to do a basic Home Value Prediction

