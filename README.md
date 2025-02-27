# Corners model
The python notebook demonstrates several steps undertaken in designing a pre-match model that uses historical football match data in order to forecast the number of corners in a future match. This notebook then demonstrates how the model can generate propreitary odds and how these can be used to develop a value betting strategy in an overs/unders market. Finally a kelly criterion is used to calculate the bet size. Need to scrape true results in order to evaluate performance on test dataset.

## Future improvements
- Additional features:
    - Team information, current position in league, cup matches, formation
    - Weather forecast
    - Referee (how much/likely is added time?)
- Improve feature selection:
    - 
- Model:
    - Assumed specific underlying distribution
    - Alternatives e.g. BDT/NN regression algorithms make no such assumption
- Odds:
    - Test data has odds but no result, train data has result but no odds
    - Historical odds would enable the simulation of long-term performance of the betting strategy
