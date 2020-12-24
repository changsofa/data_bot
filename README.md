# data_bot
Data bot for discord servers. Provides Server stats for Admin and User stats for Members.

## Planned Commands
### For Admin
* dat/channel_use (output = table of category, channel, message num, last message date)
* dat/server_daily (output = graph of message counts per day)
* dat/server_hourly (output = graph of (average or count) hourly message counts)
* dat/channel_top_user_daily (output = graph of top Nth users message count per day)

### For Users (locked to only themselves) & Admin (any user)
* dat/user_words (output = image of wordcloud given a timeframe)
* dat/user_stats (output = List of top Nth channel participation based on message count, and percent contribution to the channel's messages given a timeframe)
