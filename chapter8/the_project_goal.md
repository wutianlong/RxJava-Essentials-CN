# 项目目标

我们将在已存在的例子中创建一个新的`Activity`。这个`Activity`将会使用StackExchange API从stackoverflow检索最活跃的10位用户。使用这个信息，App将会展示一个用户的头像，姓名，名望数以及住址列表。对于每一位用户，app将会使用其居住城市和OpenWeatherMap API 来检索当地的天气预报，并展示一个小的天气图标。基于从StackOverflow检索的信息，app对列表的每一位用户将会提供一个`onClick`事件，它将会打开他们在个人信息中指定的个人网站或者打开Stack Overflow的个人主页。