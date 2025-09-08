



*>* *Create Date table*



 			Date = CALENDARAUTO()



*> Create Year Column*



 			Year = YEAR('Date'\[Date])



*> Create Quarter Column*



 			Quarter = "Q" \& QUARTER('Date'\[Date])



*> Create Month Column*



 			Month = FORMAT(('Date'\[Date]),"MMM")



*> Average Discount measure*



 			AVG discount = AVERAGE(Sales\[Discount])



*> Profit Margin measure*



 			Profit Margin = DIVIDE(\[Total Profit],\[Total Sales])



*> Total Order measure*



 			Total Order = DISTINCTCOUNT(Sales\[Order ID])



*> Total Sales measure*



 			Total Sales = SUM(Sales\[Sales])

