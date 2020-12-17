# zee5-api

### for movies<br><br>

*Request:*

```bash
http://pzee5.herokuapp.com?q=https://www.zee5.com/movies/details/vikram-vedha-2017-watch-it-on-zee5/0-0-movie_1460826290
```

*Response:*

```json
{
  "title": "Vikram Vedha",
  "description": "Vikram Vedha is a 2017 crime thriller starring R. Madhavan, Vijay Sethupathi, Varalaxmi Sarathkumar and Shraddha Srinath. Vikram, a special task force officer is on the hunt to capture dreaded gangster Vedha. After his close aides are killed in an encounter, an enraged Vedha plays mind games and unsettle Vikram’s life.",
  "thumbnail": "https://akamaividz.zee5.com/resources/0-0-movie_1460826290/list/270x152/1170x658withlog_1970575070.jpg",
  "video_url": "https://zee5vodnd.akamaized.net/hls/1080p/movies/TAMIL_MOVIES/VIKRAM_VEDHA_ta.mp4/index.m3u8?hdnea=st=1608210150~exp=1608213150~acl=/*~hmac=d5f78bcaeba1d30d6747998842a86803c55cb108c3ffca54cf9eaf382259a8dc"
}
```

### for series<br><br>

*Request:*

```bash
http://pzee5.herokuapp.com/?q=https://www.zee5.com/zee5originals/details/watch-auto-shankar-online/0-6-1593/episode-2-the-power-game/0-1-203894
```

*Response:*

```json
{
  "title": "Episode 2 - The Power Game",
  "description": "At Aasaithambi’s party, Ramajayam has a tiff with the minister. Kathiravan guides Shankar to take advantage of the situation and take over Ramajayam and Reddy's business. When Aasaithambi comes to rescue Ramajayam and Reddy at the police station, Shankar insults him. Later, Shankar takes control of the city's entire illicit liquor and brothel business.",
  "thumbnail": "https://akamaividz.zee5.com/resources/0-1-203894/list/270x152/01203894_list.jpg",
  "video_url": "https://zee5vodnd.akamaized.net/hls1/1080p/movies/MOVIE_PROJECT/PROGRAMS/ORIGINAL_CONTENT/TAMIL/AUTO_SHANKAR_TAMIL_EP02_ta_32f3c9f8.mp4/index.m3u8?hdnea=st=1608210415~exp=1608213415~acl=/*~hmac=556cc8332ecc493c86db552aa2dc9ecf17049af78f8d73f123f8853163fdd67c"
}
```
