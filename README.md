!!!Требуется модуль pytube!!!

# YoutubeDownloader
Прикрутить морду лица. (взять шаблон из 2chDownloader)<br>
Возможно добавить возможность скачивания всего канала целиком (не знаю, зачем)

Разобраться:
Traceback (most recent call last):
  File "C:\Users\d.dunaev\Downloads\YoutubePlaylistParser-main\YoutubePlaylistParser-main\ytb_plist_dwnldr.py", line 76, in <module>
    main()
  File "C:\Users\d.dunaev\Downloads\YoutubePlaylistParser-main\YoutubePlaylistParser-main\ytb_plist_dwnldr.py", line 73, in main
    list_grabber(link)
  File "C:\Users\d.dunaev\Downloads\YoutubePlaylistParser-main\YoutubePlaylistParser-main\ytb_plist_dwnldr.py", line 62, in list_grabber
    ys = yt.streams.get_highest_resolution()
  File "C:\Users\d.dunaev\AppData\Local\Programs\Python\Python310\lib\site-packages\pytube\__main__.py", line 296, in streams
    return StreamQuery(self.fmt_streams)
  File "C:\Users\d.dunaev\AppData\Local\Programs\Python\Python310\lib\site-packages\pytube\__main__.py", line 176, in fmt_streams
    stream_manifest = extract.apply_descrambler(self.streaming_data)
  File "C:\Users\d.dunaev\AppData\Local\Programs\Python\Python310\lib\site-packages\pytube\__main__.py", line 161, in streaming_data
    return self.vid_info['streamingData']
KeyError: 'streamingData'
