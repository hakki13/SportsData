# SportsData

# HOW TO USE

devtools::install_github("hakki13/SportsData")

library(SportsData)

data("NHL_Data")

head(NHL_Data)
A tibble: 6 x 49
  gamePk season gameDate            gameType gameState venue venueCity homeTeam_id homeConference homeDivision homeGoals awayTeam_id awayConference awayDivision awayGoals homeShots homePim
  <chr>  <chr>  <dttm>              <chr>    <chr>     <chr> <chr>     <chr>       <chr>          <chr>            <int> <chr>       <chr>          <chr>            <int>     <int>   <int>
1 20150~ 20152~ 2015-09-20 20:30:00 PR       Final     Brid~ Nashville NSH         Western        Central              5 FLA         Eastern        Atlantic             2        29      27
2 20150~ 20152~ 2015-09-20 23:00:00 PR       Final     TD G~ Boston    BOS         Eastern        Atlantic             2 NJD         Eastern        Metropolitan         0         0       0
3 20150~ 20152~ 2015-09-21 00:00:00 PR       Final     Brid~ Nashville NSH         Western        Central              2 FLA         Eastern        Atlantic             3        29       6
4 20150~ 20152~ 2015-09-21 23:00:00 PR       Final     Nati~ Columbus  CBJ         Eastern        Metropolitan         0 PIT         Eastern        Metropolitan         1        30      22
5 20150~ 20152~ 2015-09-21 23:00:00 PR       Final     Barc~ Brooklyn  NYI         Eastern        Metropolitan         3 PHI         Eastern        Metropolitan         2        28       6
6 20150~ 20152~ 2015-09-21 23:00:00 PR       Final     Madi~ New York  NYR         Eastern        Metropolitan         6 NJD         Eastern        Metropolitan         3        23      12
... with 32 more variables: homeTakeaways <int>, homeGiveaways <int>, homeHits <int>, homeBlocked <int>, homePowerPlayGoals <int>, homePowerPlayOpportunities <int>,
   homePowerPlayPercentage <dbl>, homeFaceOffWinPercentage <dbl>, awayShots <int>, awayPim <int>, awayTakeaways <int>, awayGiveaways <int>, awayHits <int>, awayBlocked <int>,
   awayPowerPlayGoals <int>, awayPowerPlayOpportunities <int>, awayPowerPlayPercentage <dbl>, awayFaceOffWinPercentage <dbl>, homeSkaterStats <list>, homeGoalieStats <list>,
   awaySkaterStats <list>, awayGoalieStats <list>, allPlays <list>, eventDetails <list>, recordType_H <chr>, Wins_H <int>, Losses_H <int>, OT_H <int>, recordType_A <chr>, Wins_A <int>,
   Losses_A <int>, OT_A <int>
