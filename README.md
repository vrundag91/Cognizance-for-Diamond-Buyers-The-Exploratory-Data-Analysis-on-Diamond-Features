# Introduction

<p>Diamonds are precious and people who want to buy diamond need to take care about many parameters to pay such a large amount for it. buyers do not know which parameters are affects diamond's pricing. in many well-known brands the diamonds have been sold on high price based on its cut, color, looks, transparency, and other features which only a layman knows about diamonds.Thus, buyer needs to understand the anatomy of diamond and what are the features that affects the pricing of the diamonds. following figure shows the anatomy of the diamonds.</P>

![Anatomy of Diamonds](/figures/anatomy_of_diamonds.png "Anatomy of Diamonds [Cape Town Diamond Museum -https://www.capetowndiamondmuseum.org/about-diamonds/diamond-anatomy/]")

As shown in above figure there are important features of diamonds includes table, actual depth, x(height), y(width) and z(depth). apart from these dimensions other features includes caret, cut, color, clarity. This project aims to find following insights about diamonds. (a) What is the range of caret? (b) Which ‘cut’ we find majority of the time in diamonds? (c) Which ‘color’ we find majority of the time in diamonds? (d) What can we say about the clarity of diamonds? (e) Does the total depth is depending on table width? (f) What is the range of diamond price? (g) The pricing of the diamond is depending on which factors? To find out these insights, Exploratory data analysis and various statistical operations has been performed on the dataset.

# Dataset

The dataset is takenfrom seaborn library. you can find the dataset here: https://github.com/mwaskom/seaborn-data/blob/master/diamonds.csv. The data consists of 53,940 unique records and 10 features.
<table>
    <tr>
        <td>Feature</td>
        <td>Description</td>
    </tr>
    <tr>
        <td>Carat</td>
        <td>Weight of the diamond</td>
    </tr>
    <tr>
        <td>Cut</td>
        <td>Quality of the cut (Ideal, Fair, Premium, good and very good)</td>
    </tr>
    <tr>
        <td>Clarity</td>
        <td>A categorical measurement that how clear the diamond is (I1, SI2,  SI1, VS2, VS1, VVS2, VVS1, IF)</td>
    </tr>
  <tr>
        <td>Color</td>
        <td>Diamond color from J(worst) to D(Best)</td>
    </tr>
  <tr>
        <td>Total Depth (in Percentage)</td>
        <td>Total depth percentage = z/mean(x,y)</td>
    </tr>
  <tr>
        <td>Table</td>
        <td>Width of the top of the diamond relative to widest points)</td>
    </tr>
  <tr>
        <td>x (Length)</td>
        <td>Length in mm</td>
    </tr>
  <tr>
        <td>y (Width)</td>
        <td>Width in mm</td>
    </tr>
  <tr>
        <td>z (Depth)</td>
        <td>Depth in mm</td>
    </tr>
  <tr>
        <td>Price</td>
        <td>Cost in USD</td>
    </tr>
</table>
