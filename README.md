# Phone-Manufacturing-Investment-Optimizer

This project is designed to assist a phone manufacturing startup in making strategic decisions on capital allocation between machine investments and marketing expenditures. The model optimizes machine purchases and advertising investments to maximize cash flows over a 20-year period, with a cap of up to 5 machines.

Problem Statement

You work for a new startup that is trying to manufacture phones. You are tasked with building a model which will
help determine how many machines to invest in and how much to spend on marketing. Each machine produces
noutput phones per year. Each phone sells for $pphone and costs $cphone in variable costs to produce. After nlife
years, the machine can no longer produce output, but may be scrapped for $pscrap. The machine will not be
replaced, so you may end up with zero total output before your model time period ends. Equity investment is
limited, so in each year you can spend cmachine to either buy a machine or buy advertisements. In the first year you
must buy a machine. Any other machine purchases must be made one after another (advertising can only begin
after machine buying is done). Demand for your phones starts at d1. Each time you advertise, demand increases
by gd%. The prevailing market interest rate is r.
Notes
• You may limit your model to 20 years and a maximum of 5 machines if it is helpful.
• For simplicity, assume that cmachine is paid in every year, even after all machines have shut down.
• Ensure that you can change the inputs and the outputs change as expected.
• For simplicity, assume that fractional phones can be sold, you do not need to round the quantity transacted.
The Model
Inputs
• noutput: Number of phones per machine per year
• nmachines: Number of machines purchased
• nlife: Number of years for which the machine produces phones
• pphone: Price per phone
• pscrap: Scrap value of machine
• cmachine: Price per machine or advertising year
• cphone: Variable cost per phone
• d1: Quantity of phones demanded in the first year
• gd: Percentage growth in demand for each advertisement
• r: Interest rate earned on investments
1
Outputs
• Cash flows in each year, up to 20 years
• PV of cash flows, years 1 - 20

Features

Demand Forecasting: Computes year-over-year demand growth based on initial demand and advertising investment.

Production Capacity Management: Tracks the lifespan of each machine, ensuring accurate output and financial projections.

Revenue and Cost Calculations: Calculates yearly revenue based on production, price per unit, and operational costs.

Cash Flow Analysis: Projects annual cash flows and computes the net present value (NPV) of these flows for a 20-year forecast period.

Investment Constraints: Allocates budget between machine purchase and marketing based on available capital, allowing for dynamic adjustments.


Model Inputs

Production & Machine Costs: Set number of phones per machine, cost per machine, and other fixed expenses.

Machine Lifecycle: Adjust machine lifespan to determine when output will cease and account for salvage value.

Market Variables: Include initial demand, advertising growth impact, and interest rates to reflect real-world market conditions.

Variable Costs: Set the cost to produce each phone and calculate total production expenses.


Model Outputs

Cash Flow Projections: Provides cash flow details for each year up to 20 years.

Net Present Value (NPV): Calculates NPV for cash flows, helping assess the project’s overall profitability.


Usage

This model can be customized by modifying inputs to see how changes in machine costs, production rates, demand growth, or other parameters affect the company’s financial outcomes.

The model has been created in both excel and python.
