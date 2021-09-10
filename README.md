## Welcome to my Discounted free cash flow (DFCF) project!
In this project I will create an Excel VBA template to evaluate publicly traded companies based on their financial data.
The project will explore both evaluation methods and Excel VBA coding. More specifically the following:
  - How to calculate the discount rate
  - How to calculate Weighted Average Cost of Capital (WACC)
  - Discounted free cash flow as an evaluation method
  - Preprocessing data with Excel VBA
  - Creating graphical presentations of data with Excel VBA

Everything related to finance in this project is take from the book Corporate Finance (Fifth edition) written by Jonathan Berk and Peter DeMarzo.


### The financial part (skip if you only want to see the VBA code)
## Discounted Value
The idea of the Discounted Free Cash Flow model is that if we know how much money a company will generate in the future, then we can calculate the company's present value by accounting for the cost of capital (e.g. inflation among other things). Imagine that you give out a loan of $100 today, and in one year from now the loan taker will pay you $110. Then you might wonder, what is **today's value** of that investment? That can be achieved by _discounting_ the **future value** based on the **cost of capital** according to this function:

Today's value = future value / (1 + r<sub>wacc</sub>) = $110 / (1 + 0,02) = $107.8

r<sub>wacc</sub> is the _Weighted average cost of capital_ and in this example I assumed that the cost of capital was 2% (approximately the rate of inflation). 

What I want to demonstrate with this example is **1)** How to discount future cash flows, **2)** That today's value depends on two thing: _future cash flow_ and _WACC_. **Obeserve** that when evaluating companies we will never know what the future cash flows will be nor what the WACC is, which is the reason why evaluating stock is not entirely straight forward. We will have to make assumptions about the company's financials in order to approximate the future cash flows and the WACC, which I will now go into.

## Weighted Average Cost of Capital (WACC)

## The Discounted Cash Flow Model

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
