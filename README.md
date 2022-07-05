# WebCraper-Collections

### Requirements
* [Chrome](https://www.google.com/chrome/)
* [Web Craper](https://webscraper.io/)
* Youtube

### Usage
#### [youtube_playlists](https://github.com/Buliet/WebCraper-Collections/blob/master/youtube_playlists.json)
* 根据 YouTube 播放列表地址, 爬取播放列表标题文本及 URL
* 所爬取的 URL, 可粘贴至 [4K Video Downloader](https://www.4kdownload.com/products/videodownloader/17) 或 [
Gihosoft TubeGet](https://www.gihosoft.com/free-youtube-downloader.html) 完成批量下载视频

1. 导入脚本

   > 复制 [youtube_playlists.json](https://github.com/Buliet/WebCraper-Collections/blob/master/youtube_playlists.json) 文件内容粘贴至 Chrome -> F12 -> Web Scraper -> Import Sitemap -> Sitemap JSON

2. 修改爬取网址

   >  Web Scrape -> Sitemap xx -> Edit metadata -> Start URL
   >  
   >  如 Steve TV Show, https://www.youtube.com/c/SteveTVShow/playlists
   >  
   >  **可设置多个 URL**

3. 爬取

   >  Web Scrape -> Sitemap xx -> Scrape, 等待爬取完成, 完成后可通过点击 Web Scrape -> refresh 预览数据

4. 导出数据

   >  Web Scrape -> Sitemap xx -> Export data, 支持格式: xlsx 和 csv
   
#### [youtube_playlists_plus](https://github.com/Buliet/WebCraper-Collections/blob/master/youtube_playlists_plus.json)
* 根据 YouTube 播放列表地址, 爬取播放列表标题文本及 URL
* **爬取播放列表中的视频标题及 URL** (播放列表较多时, 会比较慢, 不建议用)
