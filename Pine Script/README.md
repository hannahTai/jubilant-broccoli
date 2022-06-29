# Pine Script™ v5

## Pine Script Types

### indicator

### strategy

### library

## Compiler

### Button-Save

### Compile error

- without assigning a version number (@version) in a script
- inappropriate function in a particular type of script
- assigned NA to a variable without type keyword

## Syntax

### multiple lines for function parameters: using space to recognize, using tab is fine(must with a space).

## First Pine Script

### Hello World!
![image](assets/d472a53aa5989dbf72ae175bca47a05d2d2ee3d8676d73b280dd83dbdba96100.png)

## [Indicator function](https://www.tradingview.com/pine-script-reference/v5/#fun_indicator)

### title, shorttitle, overlay, format
![image](assets/c91bda7984e5524427ed50c9924bee24ab603ab5e48a308cf99396e3ffb61a91.png)

### precision, scale
![image](assets/1cce9e746cd031af296964853822efcdfbe4daa79f3144120d9e260522f8c01a.png)

### timeframe
![image](assets/9495d56d5b87fc9ea2901372e5dab992a9437bc3459480e16d38bd96988d1146.png)

### re-add to chart when the particular parameters changed, for example, overlay, scale

### related resources

- [format constants](https://www.tradingview.com/pine-script-reference/v5/#var_format{dot}volume)

- [scale constants](https://www.tradingview.com/pine-script-reference/v5/#var_format{dot}inherit)

## Namespaces & Libraries

### common namespaces
![image](assets/793c53f83ff9dba1573fa9c6ef4dc37d23504417744fa7e0f488300972626f1b.png)

### using custom library
![image](assets/570c94b0c7ae5654f547a82ea03064e110ec97f3212ef369acf545f3a7dc7937.png)

## Price & Indicator Series

### price, indicator series
![image](assets/23058cfaac5c0a0d1f303228f0bab01656ca0f6bf0d934104beafc7f4b5234ed.png)

## Data Types

### int, float, bool, color, string
![image](assets/25effb934567debf303582a670b9109fcec3e953588385a9a53acfafc6b1054c.png)

## Variable Declaration

### na
![image](assets/ec319b808496269e05713eb15c97f92fe3a33ae69852b4f77d82d20ebea5db15.png)

### =, := 

![image](assets/7440fa82f9e0d392027e0171e0a7e1d4a4519f5c94577010c3e77a4b62ab135b.png)

### var
![image](assets/f1b4c2a673bccf4167075733186f352f757c01ea5c07434a8343095bf081ad2d.png)

## Basic User Input

### priceInput, confirm=true
![image](assets/e46e17affc574351c3ff0ffe3e9c812ec63cf92b12ccdb7ca5b5302c9bf8cf7e.png)

### timeInput, confirm=true
![image](assets/045aa033649a330e662c66ce7118a77acceb59465927257198e218bf5c14c213.png)

### inputs
![image](assets/6256d9a682b3d4b44585930dfe0e57ea815e85c479a4339d0727f5981ba65eb5.png)

## Generating Alerts

### [alert function ](https://www.tradingview.com/pine-script-reference/v5/#fun_alert)

- create alert for Any alert() function call
![image](assets/6c9aaa868780a4c56a797403e5cd36f82d6528788cfa1e4878aa048b97b80f88.png)
- higher close alert
![image](assets/a4bbdf7ed37eb0678c102f28a11aa15584fb72e9053576e0898100a3ed655e87.png)
- lower close alert
![image](assets/e20ba0a2096d2304dda097d62e6e374d134339626e9a2fc9307586d812c003b6.png)

### [alertcondition function](https://www.tradingview.com/pine-script-reference/v5/#fun_alertcondition)

- function usage
![image](assets/e7a67dc25e091ac767c294d9a66a13912bbdee39366f891bcefc1e926ab9e2c0.png)
- alertcondition selection
![image](assets/a4a76a9a67b7364e9cb5c07f43137e38907b4c35f0973337efe80ab8577f1cf2.png)
- create alert for HC/LC Alert
![image](assets/3aaf19210ddb69358f4fc90550f835e2ef4cbec1509ce001e7defa6435093829.png)
- alert happened
![image](assets/5636a381fbd5a7c69242ed00039ddc1a2772309cc54c1be87f3e637ef6ee8f54.png)

### [variable value in alert](https://www.tradingview.com/support/solutions/43000531021-how-to-use-a-variable-value-in-alert/)

## Plotting Data

### title, color, linewidth, style, trackprice
![image](assets/869924590a5ab8027d816a36d8be4962ecc7e1a92e3459aba7af104817598fad.png)

### histbase
![image](assets/fe3583d9b47a4374333c30f3b8764868e39da0bf7453a33688c85b7f29a5c47d.png)

### offset
![image](assets/f483bbc0b669e038daca8ac3c637c99ad0553d8125ff23035c632b06e400012e.png)

### join
![image](assets/95f35684fc42d5e7425ebbd6036aef04a532f112414af306801d4463ce3084ef.png)

### editable
![image](assets/d95c18b195bfe7285d9ab079e6af02f01343de7f8b42fa984d730670601e55b1.png)

### show_last
![image](assets/0472cec5330b52079c15448bc180c00a20ab69edb4a5506d7f1edb8bb9c9bf20.png)

### display
![image](assets/3da04e0b91695417c070e17b8b6c4baf44cb65901f8cc8c7174d128df6930f1d.png)

## Moving Average Crosses

### ema
![image](assets/998389c642fad8f10b084b17be46d4aeb8627f0064bc6d6a0c84dd08d8fc4267.png)

## Hot Keys

### macOS

- search functions: option + space
- pop-up manual: command + click

## Resources

### [Pine Script BEGINNER'S GUIDE! 💹 [2022] ](https://www.youtube.com/watch?v=HYyuYgPRLpc)

- ⭐ Great Tutorial ⭐

### [Pine Script™ v5 User Manual](https://www.tradingview.com/pine-script-docs/en/v5/migration_guides/v4_to_v5_migration_guide.html)

- Official Guide

