# 本稿の目的  

本稿はイベント・ヒストリー分析(event history analysis)または生存時間分析（Survival Analysis）と呼ばれる手法の概要をまとめたものである。また、Rでこうした分析を実行する方法についても解説している。新たに個人的に勉強した内容があれば、随時追加していく。

解説は[こちらのページ](https://tsubasayamaguchi-jinrui.github.io/SurvivalAnalysis/)から。

本稿が主に参考にしたのは参考にしたのは Allison (2014) の”Event History and Survival Analysis, Second Edition”である。
また以下の書籍やサイトも参考にした。

- 杉本 (2021) 生存時間解析. 朝倉書店  
- 大橋 et al. (2021) 生存時間解析 第2版 SASによる生物統計. 東京大学出版  
- Brostrom (2021) [Event History Analysis with R, Second Edition](https://ehar.se/r/ehar2/)  
- [Survival Analysis in R](https://www.emilyzabor.com/tutorials/survival_analysis_in_r_tutorial.html)  
- [疫学のためのRハンドブック](https://epirhandbook.com/jp/survival-analysis.html)  
- [Prediction Modeling with the Cox model - all about the baseline hazard](https://missingdatasolutions.rbind.io/2022/12/cox-baseline-hazard/)   

なお、本稿の作成に使用したファイルとRのコードは筆者のGithubですべて閲覧できる。  

参考文献    
Allison, P. D. (2014). Event history and survival analysis: Regression for longitudinal event data. SAGE Publications.  
Broström, G. (2021). Event history analysis with R. CRC Press.  
大橋靖雄., 浜田知久馬., & 魚住龍史. (2021). 生存時間解析 第2版 SASによる生物統計. 東京大学出版.  
杉本知之. (2021). 生存時間解析. 朝倉書店.  