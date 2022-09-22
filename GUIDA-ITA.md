# SIMPLE RSI LONG STRATEGY 

Copy and paste the code on your Trading View console and add the strategy to the chart to start working.

You can find quickly configuration tutorial on YouTube for this algo, here: link 

# SET UP 

1. Definiamo la strategia

`
//@version=5
strategy(" Simple Strategy RSI Long (Buy & Sell) - Developed By The Quant Science™ ", 
     overlay = true, 
     default_qty_type = strategy.percent_of_equity, 
     default_qty_value = 100,
     currency = currency.EUR, 
     initial_capital = 1000, 
     commission_type = strategy.commission.percent, 
     commission_value = 0.03)
`

