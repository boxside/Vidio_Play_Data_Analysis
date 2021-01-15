

![Figure 1](https://github.com/boxside/Vidio_Play_Data_Analysis/blob/main/figure/1200px-Logo_Vidio.png)
# Vidio Play Data Analysis
  ** disclaimer: this dataset i got from vidio.com data analyst online exercise
  
  ## About
 ### Code and Resources Used 
  **Python Version:** 3.8  
  
  **Packages:** pandas, KModes, matplotlib, seaborn, sklearn, pickles

  **Dataset:**  Vidio.com
  
 ### list data details : 
* hash_content_id: content_id watched by the play
* hash_play_uuid: id of the play
* hash_visit_id: session_id of the play
* hash_watcher_id: watcher_id of the play
* hash_film_id: film_id of the play
* hash_event_id: id of the play (deprecated)
* is_login: boolean when user is logged_in when watch 
* playback_location: where user play the video (direct | embed)
* platform: platform used to play
* play_time: time the play started
* end_time: time the play ended
* referrer: attribution of the play, source of play coming from
* average_bitrate: average bitrate of play
* bitrate_range: bitrate_range set by user to play
* total_bytes: bytes used when play
* buffer_duration: buffer_duration happen while play content
* referrer_group: group of referrer
* completed: boolean which indicate the play is complete
* utm_source: campaign source 
* utm_medium: campaign source
* utm_campaign: campaign source
* player_name: engine player_name
* has_ad: indicating the play has ad or not
* flash_version: 
* os_name: os_name of device use to play 
* os_version: os_version of device use to play
* browser_name: browser name of device use to play
* browser_version: browser version of device use to play
* app_name: app_name used to play
* autoplay: indicating the play is autoplay when watched on certain platform
* is_premium: indicate the content played is a premium content
* app_version: version app being used
* city: city where the watcher_id play content
* play_duration: duration of playcontent_type: content type of content (livestreaming | vod | catchup)
* stream_type: when content_type is livestreaming, stream_type is used to categorize the livestream (EventStream | TVStream | RadioStream)
* title: title of content
* category_name: category_name of content
* film_title: title of film
* season_name: season_name of film
* genre_name: genre name of film (if the film is available) 
## data story telling

![Figure 1](https://github.com/boxside/Vidio_Play_Data_Analysis/blob/main/figure/qrppt.png)

https://docs.google.com/presentation/d/1jHOLbXEOrlFBB-pfF09s5Dy6_8WeDtBv/edit?usp=drive_web&ouid=113605775637387001912&rtpof=true
## data modelling
* user's cluster segmentation
* divided by 12 segmetntation
* machine learning using kmodes with Cao's Method
*Results : 

![Figure 1](https://github.com/boxside/Vidio_Play_Data_Analysis/blob/main/figure/Picture1.png)
