# Passenger Seamless Travel Knowledge - Concept Map
Export from ACRIS Semantic Model from Enterprise Architect. <br>

## HTML representation
https://htmlpreview.github.io/?https://github.com/rogalm/ACRIS/blob/main/Model%20Content/2%20-%20Knowledge/Passenger%20Seamless%20Travel/html/index.htm

## Concepts

| Term                  | Concept  |
|-----------------------|----------|
| ` Passenger `         | Party    | 
| ` Aircraft Operator ` | Party    | 
| ` Baggage Handler `   | Party    | 
| ` Bag Owner `          | Party    | 
| ` Issuing Agency `     | Party    | 
| ` Issuing Agency `             | Party    | 
| ` Airport Service `             | Offering | 
| ` Flight Service `             | Offering | 
| ` Filght `             | Movement | 


## Concept Maps

| Source | Association | Target|
|--------|--------| ------------ |
| Passenger | books | Airport Service |
| Baggage Handler | remove bag from | Unit Load Device |
| Operating Carrier | operates | Bag Segment |
| Passenger | walks | Aircraft Boarding Bridge Facility |
| Filght | is used to produce | Flight Service |
