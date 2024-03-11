---
layout: links
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_links

# publish date (used for seo)
# if not specified, site.time will be used.
#date: 2022-03-03 12:32:00 +0000

# for override items in _data/lang/[language].yml
#title: My title
#button_name: "My button"
# for override side_and_top_nav_buttons in _data/conf/main.yml
#icon: "fa fa-bath"

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-03-03 12:32:00 +0000
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# please use the "image_viewer_on" below to enable image viewer for individual pages or posts (_posts/ or [language]/_posts folders).
# image viewer can be enabled or disabled for all posts using the "image_viewer_posts: true" setting in _data/conf/main.yml.
#image_viewer_on: true
# please use the "image_lazy_loader_on" below to enable image lazy loader for individual pages or posts (_posts/ or [language]/_posts folders).
# image lazy loader can be enabled or disabled for all posts using the "image_lazy_loader_posts: true" setting in _data/conf/main.yml.
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false


# you can always move this content to _data/content/ folder
# just create new file at _data/content/links/[language].yml and move content below.
###########################################################
#                Links Page Data
###########################################################
page_data:
  main:
    header: "Links"
    info: "Some secret shortcuts..."

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "Conference Talks"
      type: id_talk
      color: "#8e62b4"
    - title: "Press Interview"
      type: id_news
      color: "#F4A273"

  list:
    -
    # conference talks
    - type: id_talk
      title: "GIW/ISCB-ASIA 2023"
      url: "https://www.giw-sg.com/programme"
      info: "Project Talk: ESQmodel: biologically informed evaluation of 2-D cell segmentation quality in multiplexed tissue images."
    - type: id_talk
      title: "ISMB/ECCB 2023"
      url: "https://www.iscb.org/cms_addon/conferences/ismbeccb2023/proceedings.php#MLCSB"
      info: "Proceedings Talk: SpatialSort: a Bayesian model for clustering and cell population annotation of spatial proteomics data."
    - type: id_talk
      title: "The Terry Fox New Frontiers Program in Modeling lymphoma evolution and clinical trajectory using multiomics 2022"
      url: "https://www.tfri.ca/our-research/research-project/modeling-lymphoma-evolution-and-clinical-trajectory-using-multiomics"
      info: "Poster Talk: SpatialSort: a Bayesian model for clustering and cell population annotation of spatial proteomics data."
    - type: id_talk
      title: "Taiwan-Canada Scientific Lecture Series 2021"
      url: "https://sites.google.com/view/taiwan-canada-sls"
      info: "Invited Lecture: Single cell RNA Sequencing in Cancer Research."

    # press interview
    - type: id_news
      title: "UBC In The News 2023/09/19"
      url: "https://news.ubc.ca/2023/09/19/ubc-in-the-news-992/"
      info: "Taiwanese Student Forum empowers young people to leverage culture and values to benefit the community."
    - type: id_news
      title: "Central News Agency 2023/09/18"
      url: "https://www.cna.com.tw/news/aipl/202309180173.aspx"
      info: "挺台入聯 溫哥華僑胞和學生宣揚台灣民主理念."
    - type: id_news
      title: "Singtao 2023/09/18"
      url: "https://www.singtao.ca/6378068/2023-09-18/news-%E6%BA%AB%E5%93%A5%E8%8F%AF%E5%8F%B0%E7%81%A3%E5%AD%B8%E7%94%9F%E8%AB%96%E5%A3%87%E5%88%86%E4%BA%AB%E3%80%8C%E8%BD%89%E5%8B%95%E4%B8%96%E7%95%8C%E7%9A%84%E5%8F%B0%E7%81%A3%E5%83%B9%E5%80%BC%E3%80%8D/?variant=zh-hk"
      info: "溫哥華台灣學生論壇分享「轉動世界的台灣價值」."
    - type: id_news
      title: "Pancouver 2023/09/17"
      url: "https://pancouver.ca/vancouver-taiwanese-student-forum-empowers-young-people-to-leverage-culture-and-values-to-benefit-the-community/"
      info: "Vancouver Taiwanese Student Forum empowers young people to leverage culture and values to benefit the community."
    - type: id_news
      title: "Singtao 2023/08/28"
      url: "https://www.singtao.ca/6358631/2023-08-28/news-%E6%BA%AB%E5%93%A5%E8%8F%AF%E5%8F%B0%E7%81%A3%E5%AD%B8%E7%94%9F%E8%AB%96%E5%A3%87++9%E6%9C%8817%E6%97%A5%E5%8D%91%E8%A9%A9%E5%A4%A7%E5%AD%B8%E7%99%BB%E5%A0%B4/?variant=zh-hk"
      info: "溫哥華台灣學生論壇 9月17日卑詩大學登場."
    - type: id_news
      title: "TECO Vancouver 2022/06/14"
      url: "https://www.taiwanembassy.org/cayvr/post/22285.html"
      info: "第一屆溫哥華台灣學生論壇6月12日舉行."
    - type: id_news
      title: "Central News Agency 2022/06/13"
      url: "https://www.cna.com.tw/news/aipl/202206130214.aspx"
      info: "首屆溫哥華台灣學生論壇舉行 強調台灣身分認同."
    - type: id_news
      title: "Singtao 2022/06/13"
      url: "https://www.singtao.ca/5835716/2022-06-13/post-%E9%A6%96%E5%B1%86%E5%8F%B0%E7%81%A3%E5%AD%B8%E7%94%9F%E8%AB%96%E5%A3%87-%E6%8E%A2%E8%A8%8E%E8%BA%AB%E4%BB%BD%E8%AA%8D%E5%90%8C%E5%95%8F%E9%A1%8C/?variant=zh-hk"
      info: "首屆台灣學生論壇 探討身份認同問題."

---
