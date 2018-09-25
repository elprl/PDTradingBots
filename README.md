# PDTradingBots
Trading bot scripts


## ICHIMOKU SCRIPT DETAILS
### Ideal Strategy (as per book)

Bullish :
- Price is Above Kumo
- Tenkan is above Kijun
- Chikou is above the price 26 periods in the past
- Future cloud - green
- Price is not far from Kijun and Tenkan
- Tenkan, Kijun and Chikou are not in a cloud or in the price

Bearish:
- Price below Kumo
- Tenkan is below Kijun
- Chickou is below the price 26 periods in the past
- Future cloud - red
- Price is not far from Kijun or Tenkan
- Tenkan, Kijun and Chikou are not in a cloud or in the price

### Tenkan/Kijun Crossover Strategy:

Bullish:
- Price is above Kumo or it can be a certain distance below non thick Kumo
- Tenkan crossing Kijun from below to stay above
- Chikou is in open space
- None of the elements are in the cloud or if they are it should be a thick cloud
- Optional: Future cloud is green
- Optional: Future Kumo is thin

Bearish:
- Price is below Kumo or it can be a certain distance above non thick Kumo
- Tenkan crossing Kijun from above to stay below
- Chikou is in open space
- None of the elements are in the cloud or if they are it should be a thick cloud
- Optional: Future cloud is red
- Optional: Future Kumo is thin

### Price Crossover Strategy:

Bullish:
- Price crosses over Kijun from below
- If Tenkan is below Kijun then Tenkan should be pointing upwards with its tip while Kijun is flat
- OR Tenkan is above Kijun (ideal)
- Chikou is in open space
- Span B is flat or pointing up
- If there is a Red Kumo below there should be a green Kumo forming in the future
OR at least Span A pointing upwards
- None of the elements should be in a cloud, if they are it should be a thick cloud
- Price is not far from Tenkan and Kijun
- Optional - future cloud is thin

Bearish:
- Price crosses over Kijun from above
- If Tenkan is above Kijun then Tenkan should be pointing downwards with its tip while Kijun is flat
- OR Tenkan is below Kijun (ideal)
- Chikou is in open space
- Span B is flat or pointing down
- If there is a Green Kumo below there should be a Red Kumo forming in the future
OR at least Span A pointing downwards
- None of the elements should be in a cloud, if they are it should be a thick cloud
- Price is not far from Tenkan and Kijun
- Optional - future cloud is thin


### Kumo Cloud Breakout Strategy:

Bullish:
- Price closes Above Kumo on particular time period
- If Tenkan is below Kijun then Tenkan should be pointing up
- Chikou span is in open space
- Future Span B is flat or pointing up
- If future cloud is Red (span A<Span B). Span A should be pointing up
- None of the elements should be in a cloud, if they are it should be a thick cloud
- Price is not far from Tenkan and Kijun
- Optional - future cloud is thin


Bearish:
- Price closes Below Kumo on particular time period
- If Tenkan is above Kijun then Tenkan should be pointing down
- Chikou span is in open space
- Future Span B is flat or pointing down
- If future cloud is Green (span A>Span B). Span A should be pointing down
- None of the elements should be in a cloud, if they are it should be a thick cloud
- Price is not far from Tenkan and Kijun
- Optional - future cloud is thin

### Cloud Twist Crossover Strategy:

Bullish:
- Current price is above green cloud (SpanA > SpanB)
- Price closes Above the cloud on particular time period
- If Tenkan is below Kijun then Tenkan should be pointing up
- OR Tenkan is above Kijun (ideal)
- Chikou span is in open space
- Span B is flat or pointing up
- If future cloud is Red (span A<Span B). Span A should be pointing up
- None of the elements should be in a cloud, if they are it should be a thick cloud
- Price is not far from Tenkan and Kijun
- Optional - future cloud is thin

Bearish:
- Current price is below red cloud (SpanA < SpanB)
- Price closes Below the cloud on particular time period
- If Tenkan is above Kijun then Tenkan should be pointing down
- OR Tenkan is below Kijun (ideal)
- Chikou span is in open space
- Span B is flat or pointing down
- If future cloud is Green (span A>Span B). Span A should be pointing down
- None of the elements should be in a cloud, if they are it should be a thick cloud
- Price is not far from Tenkan and Kijun
- Optional - future cloud is thin


