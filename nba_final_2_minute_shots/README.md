# NBA shots in the final 2 minutes

All shots in the NBA since 2000-01 taken in the final 2 minutes of the 4th quarter or overtime with the score within 5 points.

Data compiled from play-by-play data from [stats.nba.com](https://stats.nba.com/).

All player, team and game ids are nba.com ids. Lineup ids are "-" separated player ids.

start_time - possession start time (seconds remaining in period)
start_type - based on how previous possession ended
previous_poss_end_shooter_pid - player id of player who made or missed shot that ended previous possession
previous_poss_end_rebound_pid - player id of player who got the rebound that ended previous possession
previous_poss_end_turnover_pid - player id of player who turned the ball over to end previous possession (live ball only)
previous_poss_end_steal_pid - player id of player who stole the ball over to end previous possession
score_margin - from perspective of team on offense before the shot
shot_quality - [Shot Quality model details here](https://dblackrun.github.io/2018/09/03/pbp-shot-quality-model.html)
putback - within 2 seconds of an offensive rebound by the player who got the rebound
oreb_shot_player_id - if shot comes after an offensive rebound, player id of player who missed the shot that was rebounded
oreb_rebound_player_id - if shot comes after an offensive rebound, player id of player who got the rebound
oreb_shot_type - if shot comes after an offensive rebound, shot type of the shot that was rebounded
