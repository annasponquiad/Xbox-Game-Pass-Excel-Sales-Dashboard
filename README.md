# Xbox Game Pass — Excel Sales Dashboard

**An Excel dashboard exploring Xbox Game Pass sales and the impact of discount coupons.**



## About this project

This project was created as part of my Data Analytics training with DIO (Digital Innovation One).

The challenge was to build a sales dashboard in Excel using a dataset provided by the course. The data had already been cleaned, so my focus was on exploring the information, identifying useful business questions and presenting the findings in a clear, visual way.

I decided to investigate the impact of discount coupons on the total value of sales.

## What caught my attention

As I explored the dataset, I noticed that it contained individual subscription prices, additional purchases such as EA Play and Minecraft Season Passes, discount coupons and a final sales value for each customer.

However, the **Total Value** column already had the coupon discounts deducted.

This made me curious about how much the sales would have been worth before the discounts were applied.

Although the existing figures weren't incorrect, they only showed part of the picture.

I wanted to be able to compare the original sales value with the final amount after discounts, and understand how much of a difference the coupons were making.

## What I did

### 1. Explored the data

I started by looking through the available information to understand how the different subscription plans, additional purchases and discount coupons contributed to the total sales value.

### 2. Created a new calculation

To make the comparison possible, I added a column called **Total Value Before Discount**.

The calculation was straightforward:

`Total Value Before Discount = Total Value + Coupon Value`

This allowed me to see both the original recorded sales value and the amount after discounts were applied.

### 3. Analysed the results

I used Excel PivotTables, which allow large amounts of information to be grouped and summarised, to explore the sales figures by subscription type.

I then used the results to create charts showing the differences in value and the impact of discounts.

### 4. Built the dashboard

My aim was to create a dashboard that would make the findings easy to understand without needing to look through hundreds of rows of data.

I focused on presenting the main figures clearly, using charts and interactive elements to make the information more accessible.

## What I found

The dataset contains **295 subscription records**.

| | Value |
|---|---:|
| Sales value before discounts | R$9,755 |
| Discounts applied | R$2,122 |
| Sales value after discounts | R$7,633 |

The discounts reduced the original recorded sales value by approximately **21.8%**.

This was the main finding that stood out to me.

It also reinforced something important: before analysing a figure, we need to understand exactly what it represents.

In this case, both values are useful, but they answer different questions.

The value before discounts shows the original value of the subscriptions and add-ons, while the value after discounts shows what remained once the coupons were deducted.

## What I would investigate next

Having seen the overall impact of the coupons, I think it would be interesting to understand **how the discounts are being distributed across customers**.

My recommendation would be to explore the frequency and value of coupons across the different subscription types and plans.

For example:

- Are some subscription plans receiving discounts more frequently than others?
- Are certain customers receiving larger discounts?
- What percentage of the original sales value is being discounted for each subscription group?
- Could the discounts be encouraging customers to choose particular plans or purchase additional products?

These questions could help the business better understand its discount strategy.

However, more information about customer behaviour would be needed before deciding whether the discounts should be changed.

## Tools and skills I practised

I used Microsoft Excel to work through the project, practising:

- **PivotTables:** Grouping and summarising sales information.
- **Excel formulas:** Creating an additional sales value calculation.
- **Charts:** Comparing figures and communicating results visually.
- **Dashboard design:** Organising information into a clear, accessible layout.
- **Business analysis:** Asking questions, exploring patterns and considering what the findings might mean.

## How to explore the dashboard

The completed Excel workbook is included in this repository.

To view it:

1. Download the `.xlsx` file.
2. Open it in the desktop version of Microsoft Excel for the best viewing experience.
3. Explore the dashboard and use its interactive features to examine the results.

The workbook has been arranged to open directly on the dashboard, with the supporting worksheets hidden to keep the presentation focused.

## What I learned

One of my biggest takeaways from this project was that creating a dashboard isn't just about deciding which charts to use.

It's about understanding the data, asking the right questions and deciding which information would actually be useful to someone looking at the results.

I particularly enjoyed exploring the dataset and realising that a small additional calculation could give me a different perspective on the sales figures.

This project also helped me become more comfortable with PivotTables, charts and working with data in Excel.

And perhaps most importantly, it reminded me how much I enjoy investigating information, questioning what I'm seeing and finding ways to make it easier to understand.

---

*This is a learning project completed as part of the DIO Data Analytics programme, using a dataset supplied for educational purposes. It is not affiliated with Microsoft or Xbox.*
