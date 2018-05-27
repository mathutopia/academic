+++
title = "Detecting Ponzi Schemes on Ethereum: Towards Healthier Blockchain Technology"
date = 2018-05-25T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Weili Chen","Zibin Zheng","Jiahui Cui","Edith Ngai","Peilin Zheng","Yuren Zhou"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In Proceedings of the 2018 *World Wide Web Conference*."
publication_short = "In *WWW2018*"




# Abstract and optional shortened version.
abstract = "This paper proposes an approach to detect Ponzi schemes implemented in smart contract on Ethereum blockchain by using data mining and machine learning methods. The experimental results show that the proposed approach can achieve high accuracy for practical use. More importantly, the approach can be used to detect Ponzi schemes even at the moment of its creation. By using the proposed approach, we estimate that there are more than 400 Ponzi schemes running on Ethereum."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename of your project in `content/project/`.
#   Otherwise, set `projects = []`.
projects = ["anti-scam.md"]

# Links (optional).
url_pdf = "files/pdf/detectponzi.pdf"
# url_preprint = ""
# url_code = "#"
# url_dataset = "#"
# url_project = "#"
# url_slides = "#"
# url_video = "#"
# url_poster = "#"
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
# image = "ponziwordcloud.jpg"
caption = "My caption :smile:"

+++

Blockchain technology becomes increasingly popular. It also attracts scams, for example, Ponzi scheme, a classic fraud, has been found making a notable amount of money on Blockchain, which has a very negative impact. To help dealing with this issue, we propose an approach to detect Ponzi schemes on Blockchain by using data mining and machine learning methods. By verifying smart contracts on Ethereum, we first extract features from user accounts and operation codes of the smartcontracts and then build a classification model to detect latent Ponzi schemes implemented as smart contracts. Using the manually checked samples and XGBoost, a regression tree model based on extracted account features and code features is build. The experimental results indicate that the proposed model has high accurate and can be used to detect latent smart Ponzi schemes in practice. The most significance results are that using our extracted code features that are publicly accessible in any running contract, is enough to build a practical model for detecting Ponzi scheme contract at the moment of its creation. In addition, we estimate that there are more than 400 smart Ponzi schemes on Ethereum, which are far more than the previous estimation. Based on these results, we propose to build a uniform platform to evaluate and monitor every created smart contract for early warning of scams.
   
In the future, we are going to further this study in three aspects. Firstly, to extend the ground truth data and improve the classification model. As the number of smart contracts having source codes keep increasing every day, it is possible to extend the ground truth data by manually checking the source codes. With more ground truth data, more accurate and credible model can be developed. Secondly, to build a unified platform to evaluate and score every smart contract for every possible scam. We have noticed that there is an open source project on Github to keep track of all the current Ethereum scams17. However, the website collects data by manual user reports and combines them. We are trying to establish a similar website focusing on detecting smart contracts by data mining methods. Thirdly, to study other kinds of scams. Except for smart Ponzi scheme, many other scams are taking the advantage of Blockchain technology. It is necessary to study this question to promote the development of Blockchain technology.  
