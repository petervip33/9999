hostname = *.iydsj.com,*.k.sohu.com,*.kakamobi.cn,*.kingsoft-office-service.com,*.meituan.net,*.musical.ly,*.ofo.com,*.pstatp.com,*.snssdk.com,*.uve.weibo.com,*.ydstatic.com,*pi.feng.com,4gimg.map.qq.com,a.apicloud.com,a.qiumibao.com,a.wkanx.com,acs.m.taobao.com,act.vip.iqiyi.com,api.21jingji.com,api.caijingmobile.com,api.chelaile.net.cn,api.daydaycook.com.cn,api.douban.com,api.gotokeep.com,api.haohaozhu.cn,api.huomao.com,api.intsig.net,api.izuiyou.com,api.jr.mi.com,api.jxedt.com,api.kkmh.com,api.m.jd.com,api.mgzf.com,api.qbb6.com,api.psy-1.com,api.rr.tv,api.smzdm.com,api.tv.sohu.com,api.vistopia.com.cn,api.wallstreetcn.com,api.xiachufang.com,api.zhihu.com,api.zhuishushenqi.com,api*.tiktokv.com,api5.futunn.com,api-mifit*.huami.com,api-release.wuta-cam.com,app.58.com,app.api.ke.com,app.bilibili.com,appconf.mail.163.com,app.mixcapp.com,app.variflight.com,app.wy.guahao.com,app.yinxiang.com,b.zhuishushenqi.com,c.m.163.com,cap.caocaokeji.cn,capi.mwee.cn,cdn.moji.com,channel.beitaichufang.com,clientaccess.10086.cn,client.mail.163.com,cms.daydaycook.com.cn,consumer.fcbox.com,creditcard.ecitic.com,daoyu.sdo.com,dl.app.gtja.com,dxy.com,e.dangdang.com,easyreadfs.nosdn.127.net,gateway.shouqiev.com,guide-acs.m.taobao.com,g.cdn.pengpengla.com,gw.alicdn.com,gw-passenger.01zhuanche.com,huichuan.sm.cn,i.weread.qq.com,i.ys7.com,iapi.bishijie.com,iface.iqiyi.com,ih2.ireader.com,img01.10101111cdn.com,img.jiemian.com,interface.music.163.com,ios.lantouzi.com,ios.wps.cn,m*.amap.com,m.client.10010.com,m.creditcard.ecitic.com,m.ibuscloud.com,m.poizon.com,m.yap.yahoo.com,mapi.mafengwo.cn,media.qyer.com,mlife.cmbchina.com,mlife.jf365.boc.cn,mob.mddcloud.com.cn,mobi.360doc.com,mp.weixin.qq.com,mrobot.pcauto.com.cn,mrobot.pconline.com.cn,ms.jr.jd.com,msspjh.emarbox.com,newsso.map.qq.com,nnapp.cloudbae.cn,open.qyer.com,pic1cdn.cmbchina.com,pic*.chelaile.net,portal-xunyou.qingcdn.com,pss.txffp.com,r.inews.qq.com,render.alipay.com,restapi.iyunmai.com,resrelease.wuta-cam.com,richmanapi.jxedt.com,rtbapi.douyucdn.cn,service.4gtv.tv,smkmp.96225.com,slapi.oray.net,snailsleep.net,sp.kaola.com,ss0.bdstatic.com,ssl.kohsocialapp.qq.com,static.vuevideo.net,static1.keepcdn.com,status.boohee.com,support.you.163.com,s.youtube.com,thor.weidian.com,tiku.zhan.com,weibointl.api.weibo.cn,www.bodivis.com.cn,www.dandanzan.com,www.flyertea.com,www.youtube.com,yxyapi*.drcuiyutao.com,www.zhihu.com,www.zybang.com,youtubei.googleapis.com,zhidao.baidu.com

# Redirect Google Service
^https?:\/\/(www.)?(g|google)\.cn url 302 https://www.google.com

# Redirect HTTP to HTTPS
^https?:\/\/(www.)?taobao\.com\/ url 302 https://taobao.com/
^https?:\/\/(www.)?jd\.com\/ url 302 https://www.jd.com/
^https?:\/\/(www.)?mi\.com\/ url 302 https://www.mi.com/
^https?:\/\/you\.163\.com\/ url 302 https://you.163.com/
^https?:\/\/(www.)?suning\.com/ url 302 https://suning.com/
^https?:\/\/(www.)?yhd\.com url 302 https://yhd.com/

# Redirect False to True
# > IGN China to IGN Global
^https?:\/\/(www.)?ign\.xn--fiqs8s\/ url 302 http://cn.ign.com/ccpref/us
# > Fake Website Made By Makeding
^https?:\/\/(www.)?abbyychina\.com\/ url 302 http://www.abbyy.cn/
^https?:\/\/(www.)?bartender\.cc\/ url 302 https://cn.seagullscientific.com
^https?:\/\/(www.)?betterzip\.net\/ url 302 https://macitbetter.com/
^https?:\/\/(www.)?beyondcompare\.cc\/ url 302 https://www.scootersoftware.com/
^https?:\/\/(www.)?bingdianhuanyuan\.cn\/ url 302 http://www.faronics.com/zh-hans/
^https?:\/\/(www.)?chemdraw\.com\.cn\/ url 302 http://www.cambridgesoft.com/
^https?:\/\/(www.)?codesoftchina\.com\/ url 302 https://www.teklynx.com/
^https?:\/\/(www.)?coreldrawchina\.com\/ url 302 https://www.coreldraw.com/cn/
^https?:\/\/(www.)?crossoverchina\.com\/ url 302 https://www.codeweavers.com/
^https?:\/\/(www.)?easyrecoverychina\.com\/ url 302 https://www.ontrack.com/
^https?:\/\/(www.)?ediuschina\.com\/ url 302 https://www.grassvalley.com/
^https?:\/\/(www.)?flstudiochina\.com\/ url 302 https://www.image-line.com/flstudio/
^https?:\/\/(www.)?formysql\.com\/ url 302 https://www.navicat.com.cn
^https?:\/\/(www.)?guitarpro\.cc\/ url 302 https://www.guitar-pro.com/
^https?:\/\/(www.)?huishenghuiying\.com\.cn\/ url 302 https://www.corel.com/cn/
^https?:\/\/(www.)?iconworkshop\.cn\/ url 302 https://www.axialis.com/iconworkshop/
^https?:\/\/(www.)?imindmap\.cc\/ url 302 https://imindmap.com/zh-cn/
^https?:\/\/(www.)?jihehuaban\.com\.cn\/ url 302 https://sketch.io/
^https?:\/\/(www.)?keyshot\.cc\/ url 302 https://www.keyshot.com/
^https?:\/\/(www.)?mathtype\.cn\/ url 302 http://www.dessci.com/en/products/mathtype/
^https?:\/\/(www.)?mindmanager\.cc\/ url 302 https://www.mindjet.com/
^https?:\/\/(www.)?mindmapper\.cc\/ url 302 https://mindmapper.com
^https?:\/\/(www.)?mycleanmymac\.com\/ url 302 https://macpaw.com/cleanmymac
^https?:\/\/(www.)?nicelabel\.cc\/ url 302 https://www.nicelabel.com/
^https?:\/\/(www.)?ntfsformac\.cc\/ url 302 https://www.tuxera.com/products/tuxera-ntfs-for-mac-cn/
^https?:\/\/(www.)?ntfsformac\.cn\/ url 302 https://www.paragon-software.com/ufsdhome/zh/ntfs-mac/
^https?:\/\/(www.)?overturechina\.com\/ url 302 https://sonicscores.com/overture/
^https?:\/\/(www.)?passwordrecovery\.cn\/ url 302 https://cn.elcomsoft.com/aopr.html
^https?:\/\/(www.)?pdfexpert\.cc\/ url 302 https://pdfexpert.com/zh
^https?:\/\/(www.)?ultraiso\.net\/ url 302 https://cn.ezbsystems.com/ultraiso/
^https?:\/\/(www.)?vegaschina\.cn\/ url 302 https://www.vegas.com/
^https?:\/\/(www.)?xmindchina\.net\/ url 302 https://www.xmind.cn/
^https?:\/\/(www.)?xshellcn\.com\/ url 302 https://www.netsarang.com/products/xsh_overview.html
^https?:\/\/(www.)?yuanchengxiezuo\.com\/ url 302 https://www.teamviewer.com/zhcn/
^https?:\/\/(www.)?zbrushcn\.com\/ url 302 http://pixologic.com/

# TikTok
(?<=(carrier|account|sys)_region=)CN url 307 JP

# Advertising Block
# 0~9
# > 21epaper
^https?:\/\/api\.21jingji\.com\/ad\/ - reject
# > 360doc
^https?:\/\/mobi\.360doc\.com\/v\d{2}\/Ajax\/festival\.ashx\?op=getfestivaltheme - reject
# > 58同城
^https?:\/\/app\.58\.com\/api\/home\/(advertising|appadv)\/ - reject
^https?:\/\/app\.58\.com\/api\/home\/invite\/popupAdv - reject
^https?:\/\/app\.58\.com\/api\/log\/ - reject
^https?:\/\/.+\.58cdn\.com\.cn\/brandads\/ - reject

# A
# > Alibaba
^https?:\/\/gw\.alicdn\.com\/.*\.jpg_(9\d{2}|\d{4}) - reject
# >> 闲鱼
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.taobao\.idle\.home\.welcome\/ - reject
# >> 飞猪
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.trip\.activity\.querytmsresources\/ - reject
# >> 淘票票
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.film\.mtopadvertiseapi\.queryadvertise\/ - reject
# >> 口碑
^https?:\/\/render\.alipay\.com\/p\/s\/h5data\/prod\/spring-festival-2019-h5data\/popup-h5data\.json - reject
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.o2o\.ad\.gateway\.get\/ - reject
^https?:\/\/guide-acs\.m\.taobao\.com\/gw\/mtop\.taobao\.wireless\.home\.splash\.awesome\.get\/ - reject
# >> UC
^https?:\/\/huichuan\.sm\.cn\/jsad - reject
^https?:\/\/iflow\.uczzd\.cn\/log\/ - reject
# >> AMap
^https?:\/\/m\d\.amap\.com\/ws\/valueadded\/alimama\/splash_screen\/ - reject
# > AcFun
^https?:\/\/aes\.acfun\.cn\/s\?adzones - reject
# > 爱回收
^https?:\/\/gw\.aihuishou\.com\/app-portal\/home\/getadvertisement - reject
# > APICloud
^https?:\/\/a\.apicloud\.com\/start_page\/ - reject

# B
# > Baidu
# >> 百度网盘
^https?:\/\/update\.pan\.baidu\.com\/statistics - reject
^https?:\/\/issuecdn\.baidupcs\.com\/issue\/netdisk\/guanggao\/ - reject
# >> 百度贴吧
^https?:\/\/c\.tieba\.baidu\.com\/c\/s\/splashSchedule - reject
^https?:\/\/c\.tieba\.baidu\.com\/c\/f\/forum\/getAdInfo - reject
^https?:\/\/c\.tieba\.baidu\.com\/\w+\/\w+\/(sync|newRnSync|mlog) - reject
# >> 百度地图
# ^https?:\/\/.+\/client\/phpui2\/ - reject
^https?:\/\/ss0\.bdstatic\.com/.+_\d{3}_\d{4}\.jpg - reject
# > ByteDance
^https?:\/\/.+\.pstatp\.com\/img\/ad - reject
^https?:\/\/.+\.(musical|snssdk|tiktokv)\.(com|ly)\/(api|motor)\/ad\/ - reject
^https?:\/\/dsp\.toutiao\.com\/api\/xunfei\/ads\/ - reject
^https?:\/\/.+\.snssdk\.com\/motor\/operation\/activity\/display\/config\/V2\/ - reject
# > bilibili
^https?:\/\/app\.bilibili\.com\/x\/v2\/splash\/ - reject
# > 抱抱
^https?:\/\/www\.myhug\.cn\/ad\/ - reject
# > 百词斩
^https?:\/\/7n\.bczcdn\.com\/launchad\/ - reject
# > 贝太厨房
^https?:\/\/channel\.beitaichufang\.com\/channel\/api\/v\d\/promote\/ios\/start\/page - reject
# > 币世界
^https?:\/\/iapi\.bishijie\.com\/actopen\/advertising\/ - reject
# > 贝壳找房
^https?:\/\/app\.api\.ke\.com\/config\/config\/bootpage - reject
# > Bank of China
^https?:\/\/mlife\.jf365\.boc\.cn\/AppPrj\/FirstPic\.do\? - reject
# > Boohee
^https?:\/\/status\.boohee\.com\/api\/v\d\/app_square\/start_up_with_ad - reject

# C
# > China CITIC Bank
^https?:\/\/m\.creditcard\.ecitic\.com\/citiccard\/mbk\/.+\/appStartAdv - reject
# > Industrial and Commercial Bank of China
^https?:\/\/v\.icbc\.com\.cn\/userfiles\/Resources\/WAP\/advertisement\/ - reject
# > China Merchants Bank
^https?:\/\/mlife\.cmbchina\.com/ClientFaceService\/preCacheAdvertise\.json - reject
^https?:\/\/mlife\.cmbchina\.com\/ClientFaceService\/getAdvertisement\.json - reject
^https?:\/\/pic1cdn\.cmbchina\.com\/appinitads\/ - reject
# > China Merchants Bank
^https?:\/\/www\.cmbc\.com\.cn\/m\/image\/loadingpage\/ - reject
# > China Guangfa Bank
^https?:\/\/mps\.95508\.com\/mps\/club\/cardPortals\/adv\/.{25}\.jpg - reject
# > China Mobile
^https?:\/\/clientaccess\.10086\.cn\/biz-orange\/DN\/init\/startInit - reject
# > China Unicom
^https?:\/\/m\.client\.10010\.com\/mobileService\/customer\/accountListData\.htm - reject
^https?:\/\/m\.client\.10010\.com\/uniAdmsInterface\/getWelcomeAd - reject
# > CNTV
^https?:\/\/cntv\.hls\.cdn\.myqcloud\.com\/.+\?maxbr=850 - reject
^https?:\/\/asp\.cntv\.myalicdn\.com\/.+\?maxbr=850 - reject
^https?:\/\/www\.cntv\.cn\/nettv\/adp\/ - reject
^https?:\/\/v\.cctv\.com\/.+850 - reject
# > 车来了
^https?:\/\/api\.chelaile\.net\.cn\/adpub\/ - reject
# ^https?:\/\/(api|atrace)\.chelaile\.net\.cn\/adpub\/ - reject
^https?:\/\/api\.chelaile\.net\.cn\/goocity\/advert\/ - reject
# ^https?:\/\/atrace\.chelaile\.net\.cn\/exhibit\?&adv_image - reject
^https?:\/\/pic\d\.chelaile\.net\.cn\/adv\/ - reject
# > 曹操出行
^https?:\/\/cap\.caocaokeji\.cn\/advert-bss\/ - reject
# > CamScanner
^https?:\/\/api\.intsig\.net\/user\/cs\/operating\/app\/get_startpic\/ - reject
# > 财经
^https?:\/\/api\.caijingmobile\.com\/(ad|advert)\/ - reject

# D
# > 豆瓣
# (154.8.131.* 疑似自签证书不可验证)
^https?:\/\/.+\/v2\/app_ads\/ - reject
# > 斗鱼
^https?:\/\/rtbapi\.douyucdn\.cn\/japi\/sign\/app\/getinfo - reject
# > 当当
^https?:\/\/mapi\.dangdang\.com\/index\.php\?action=init - reject
^https?:\/\/e\.dangdang\.com\/.+getDeviceStartPage - reject
# > DayDayCook
^https?:\/\/api\.daydaycook\.com\.cn\/daydaycook\/server\/ad\/ - reject
^https?:\/\/cms\.daydaycook\.com\.cn\/api\/cms\/advertisement\/ - reject
# > 蛋蛋赞
^https?:\/\/www\.dandanzan\.com\/res\/gdsefse\.js - reject
# > 叨鱼
^https?:\/\/daoyu\.sdo\.com\/api\/userCommon\/getAppStartAd - reject
# > 丁香医生
^https?:\/\/dxy\.com\/app\/i\/ask\/biz\/feed\/launch - reject
# > 嘀嗒出行
^https?:\/\/capis(-slb)?\.didapinche\.com\/ad\/ - reject
^https?:\/\/www\.didapinche\.com\/app\/adstat\/ - reject

# E
# > eLong
^https?:\/\/123\.59\.31\.1\/(adgateway|adv)\/ - reject
^https?:\/\/119\.18\.193\.135\/(adgateway|adv)\/ - reject
# > e代驾
^https?:\/\/pic\.edaijia\.cn\/adsplash\/ - reject

# F
# > Foodie
^https?:\/\/foodie-api\.yiruikecorp\.com\/v\d\/(banner|notice)\/overview - reject
# > FOTOABLE
^https?:\/\/cdn\.api\.fotoable\.com\/Advertise\/ - reject
# > 飞客茶馆
^https?:\/\/www\.flyertea\.com\/source\/plugin\/mobile\/mobile\.php\?module=advis - reject
# > 飞常准
^https?:\/\/app\.variflight\.com\/ad\/ - reject
^https?:\/\/app\.variflight\.com\/v\d\/advert\/ - reject
# > FENG
^https?:\/\/api\.feng\.com\/v\d\/advertisement\/.*Claunch - reject

# G
# > Google
^https?:\/\/.+\.googlevideo\.com\/.+&oad - reject
^https?:\/\/.+\.googlevideo\.com\/.+ctier - reject
^https?:\/\/youtubei\.googleapis\.com\/youtubei\/.+ad_ - reject
^https?:\/\/youtubei\.googleapis\.com\/youtubei\/.+log_ - reject
^https?:\/\/.+\.youtube\.com\/get_midroll_ - reject
^https?:\/\/premiumyva\.appspot\.com\/vmclickstoadvertisersite - reject
^https?:\/\/.+\.youtube\.com\/api\/stats\/ads - reject
^https?:\/\/.+\.youtube\.com\/api\/stats\/.+adformat - reject
^https?:\/\/.+\.youtube\.com\/pagead\/ - reject
^https?:\/\/.+\.youtube\.com\/ptracking - reject
# > Gofun
^https?:\/\/gateway\.shouqiev\.com\/fsda\/app\/bootImage\.json - reject
# > GoodBodivis
^https?:\/\/www\.bodivis\.com\.cn\/app\/splashAdvertise - reject
# > 国泰君安
^https?:\/\/dl\.app\.gtja\.com\/dzswem\/kvController\/.+\.jpg$ - reject

# H
# > 杭州公交
^https?:\/\/m\.ibuscloud.com\/v2\/app\/getStartPage - reject
# > 杭州市·市民卡
^https?:\/\/smkmp\.96225.com\/smkcenter\/ad/ - reject
# > 虎扑
^https?:\/\/games\.mobileapi\.hupu\.com\/.+\/(interfaceAdMonitor|interfaceAd)\/ - reject
# > 韩剧社
^https?:\/\/47\.97\.20\.12\/ad\/ - reject
# > 火猫
^https?:\/\/api\.huomao\.com\/channels\/loginAd - reject
# > HiveBox
^https?:\/\/consumer\.fcbox\.com\/v\d\/ad\/ - reject
# > 好好住
^https?:\/\/api\.haohaozhu\.cn\/index\.php\/home\/AppInit\/getStartPhoto - reject

# I
# > iFlytek
^https?:\/\/imeclient\.openspeech\.cn\/adservice\/ - reject
# > iQiyi
^https?:\/\/iface\.iqiyi\.com\/api\/getNewAdInfo - reject
^https?:\/\/.+\/(mixer|track2)\? - reject
^https?:\/\/act\.vip\.iqiyi\.com\/interact\/api\/show.do - reject
^https?:\/\/act\.vip\.iqiyi\.com\/interact\/api\/v2\/show - reject
# > iReader
^https?:\/\/ih2\.ireader\.com\/zyapi\/bookstore\/ad\/ - reject
^https?:\/\/ih2\.ireader\.com\/zyapi\/self\/screen\/ad - reject
^https?:\/\/ih2\.ireader\.com\/zycl\/api\/ad\/ - reject

# J
# > JD
^https?:\/\/api\.m\.jd.com\/client\.action\?functionId=(start|queryMaterialAdverts) - reject
^https?:\/\/(bdsp-x|dsp-x)\.jd\.com\/adx\/ - reject
^https?:\/\/ms\.jr\.jd\.com\/gw\/generic\/base\/na\/m\/adInfo - reject
^https?:\/\/ms\.jr\.jd\.com\/gw\/generic\/aladdin\/na\/m\/getLoadingPicture - reject
# > 界面新闻
^https?:\/\/img\.jiemian\.com\/ads\/ - reject
# > 驾校一点通
^https?:\/\/api\.jxedt\.com\/ad\/ - reject
^https?:\/\/richmanapi\.jxedt\.com\/api\/ad\/ - reject
# > 驾考宝典
^https?:\/\/.+\.kakamobi\.cn\/api\/open\/v\d\/advert-sdk\/ - reject

# K
# > Keep
^https?:\/\/api\.gotokeep\.com\/ads - reject
# > Kingsoft WPS
^https?:\/\/ios\.wps\.cn\/ad-statistics-service - reject
^https?:\/\/mobile-pic\.cache\.iciba\.com\/feeds_ad\/ - reject
^https?:\/\/.+\.kingsoft-office-service\.com\/ad - reject
# > Kingsoft PowerWord
^https?:\/\/dict-mobile\.iciba\.com\/interface\/index\.php\?.+(c=ad|collectFeedsAdShowCount|KSFeedsAdCardViewController) - reject
^https?:\/\/service\.iciba\.com\/popo\/open\/screens\/v\d\?adjson - reject
# > 快看漫画
^https?:\/\/api\.kkmh\.com\/.+(ad|advertisement)\/ - reject
# > Kuwo
^https?:\/\/122\.14\.246\.33\/MobileAdServer\/ - reject
^https?:\/\/(2(5[0-5]{1}|[0-4]\d{1})|[0-1]?\d{1,2})(\.(2(5[0-5]{1}|[0-4]\d{1})|[0-1]?\d{1,2})){3}\/EcomResourceServer/AdPlayPage/adinfo - reject
# > 看理想
^https?:\/\/api\.vistopia\.com\.cn\/api\/v\d\/home\/advertisement - reject

# L
# > Le
^https?:\/\/.+\/letv-gug\/ - reject
# > 来疯直播
^https?:\/\/api\.laifeng\.com\/v\d\/start\/ads - reject
# > 懒投资
^https?:\/\/ios\.lantouzi\.com\/api\/startpage - reject

# M
# > MI
^https?:\/\/api\.m\.mi\.com\/v\d\/app\/start - reject
^https?:\/\/api\.jr\.mi\.com\/v\d\/adv\/ - reject
^https?:\/\/api\.jr\.mi\.com\/jr\/api\/playScreen - reject
# > MI_Fit
^https?:\/\/api-mifit.+\.huami\.com\/discovery\/mi\/discovery\/.+_ad\? - reject
# > MogoRenter
^https?:\/\/api\.mgzf\.com\/renter-operation\/home\/startHomePage - reject
# > MojiWeather
^https?:\/\/cdn\.moji\.com\/(adoss|adlink)\/ - reject
# > 埋堆堆
^https?:\/\/mob\.mddcloud\.com\.cn\/api\/(ad|advert)\/ - reject
# > 漫画人
^https?:\/\/mangaapi\.manhuaren\.com\/v\d\/public\/getStartPageAds - reject
# > 美团
^https?:\/\/img\.meituan\.net\/(adunion|display|midas)\/.+\.(gif|jpg|jpg\.webp)$ - reject
^https?:\/\/p\d\.meituan\.net\/wmbanner\/[A-Za-z0-9]+\.jpg - reject
^https?:\/\/p\d\.meituan\.net\/movie\/[A-Za-z0-9]+\.jpg\?may_covertWebp - reject
^https?:\/\/s3plus\.meituan\.net\/.+\/linglong\/.+\.(gif|jpg|mp4) - reject
# > 美味不用等
^https?:\/\/capi.mwee.cn/app-api/V\d{2}/app/(ad|getstartad) - reject
# > 咪咕
^https?:\/\/.+\/v\d\/iflyad\/ - reject
^https?:\/\/.+\/cdn-adn\/ - reject
^https?:\/\/ggic\d?\.cmvideo\.cn\/ad\/ - reject
^https?:\/\/.+/img\/ad\.union\.api\/ - reject
# > 秒拍
^https?:\/\/b-api\.ins\.miaopai\.com\/\d\/ad/ - reject
# > 马蜂窝
^https?:\/\/mapi\.mafengwo\.cn\/ad\/ - reject
^https?:\/\/mapi\.mafengwo\.cn\/travelguide\/ad\/ - reject

# N
# > NetEase Mail
^https?:\/\/appconf\.mail\.163\.com\/mmad\/ - reject
# > NetEase Youdao
^https?:\/\/oimage([a-z])([0-9])\.ydstatic\.com\/.+adpublish - reject
^https?:\/\/dsp-impr2\.youdao\.com\/adload.s\? - reject
# > NetEase News
^https?:\/\/c\.m\.163\.com\/nc\/gl\/ - reject
# > NetEase MoneyKeeper
^https?:\/\/client\.mail\.163\.com\/apptrack\/confinfo\/searchMultiAds - reject
# > NetEase CloudMusic
^https?:\/\/.+\/eapi\/(ad|log)\/ - reject
# > NetEase 考拉
^https?:\/\/sp\.kaola\.com\/api\/openad - reject
# > NetEase Yanxuan
^https?:\/\/support\.you\.163\.com\/xhr\/boot\/getBootMedia\.json - reject
# > NetEase SnailReader
^https?:\/\/easyreadfs\.nosdn\.127\.net\/ad-material\/ - reject
# > 爱南宁
^https?:\/\/nnapp\.cloudbae\.cn\/mc\/api\/advert/ - reject
# > NationalGeographic
^https?:\/\/dili\.bdatu\.com\/jiekou\/ad\/ - reject
# > NationalGeographicChina
^https?:\/\/wap\.ngchina\.cn\/news\/adverts\/ - reject

# O
# > ofo
^https?:\/\/supportda\.ofo\.com\/adaction\? - reject
^https?:\/\/ma\.ofo\.com\/ads\/ - reject
^https?:\/\/activity2\.api\.ofo\.com\/ofo\/Api\/v2\/ads - reject
^https?:\/\/ma\.ofo\.com\/adImage\/ - reject
# > Oray
^https?:\/\/slapi.oray.net/client/ad - reject

# P
# > PeanutWiFiMpass
^https?:\/\/cmsapi\.wifi8\.com\/v\d\/(emptyAd|adNew)\/ - reject
# > 票根
^https?:\/\/pss\.txffp\.com\/piaogen\/images\/launchScreen/ - reject

# Q
# > Qdaily
^https?:\/\/app3\.qdaily\.com\/app3\/boot_advertisements\.json - reject
^https?:\/\/notch\.qdaily\.com\/api\/v2\/boot_ad - reject
# > 穷游
^https?:\/\/open\.qyer\.com\/qyer\/startpage\/ - reject
^https?:\/\/open\.qyer.com\/qyer\/config\/get - reject
^https?:\/\/media\.qyer\.com\/ad\/ - reject
# > 亲宝宝
^https?:\/\/api\.qbb6\.com\/ad\/ - reject

# R
# > 人人视频
^https?:\/\/msspjh\.emarbox\.com\/getAdConfig - reject
^https?:\/\/api\.videozhishi\.com\/api\/getAdvertising - reject
^https?:\/\/api\.rr\.tv\/ad\/ - reject

# S
# > Sina
^https?:\/\/edit\.sinaapp\.com\/ua\?t=adv - reject
# > Sina Weibo
^https?:\/\/sdkapp\.uve\.weibo\.com\/interface\/sdk\/sdkad\.php - reject
^https?:\/\/wbapp\.uve\.weibo\.com\/wbapplua\/wbpullad\.lua - reject
^https?:\/\/sdkapp\.uve\.weibo\.com/\interface\/sdk\/actionad\.php - reject
^https?:\/\/weibointl\.api\.weibo\.cn\/portal\.php\?a=get_coopen_ads - reject
# > Sina 天气通
^https?:\/\/tqt\.weibo\.cn\/overall\/redirect\.php\?r=tqt_sdkad - reject
^https?:\/\/tqt\.weibo\.cn\/overall\/redirect\.php\?r=tqtad - reject
^https?:\/\/tqt\.weibo\.cn\/.+advert\.index - reject
^https?:\/\/tqt\.weibo\.cn\/api\/advert\/ - reject
# > Sohu
^https?:\/\/api\.k\.sohu\.com\/api\/news\/adsense - reject
^https?:\/\/pic\.k\.sohu\.com\/img8\/wb\/tj\/ - reject
^https?:\/\/s1\.api\.tv\.itc\.cn\/v4\/mobile\/control\/switch\.json - reject
^https?:\/\/api\.tv\.sohu\.com\/agg\/api\/app\/config\/bootstrap - reject
# > StarFans
^https?:\/\/g\.cdn\.pengpengla\.com\/starfantuan\/boot-screen-info\/ - reject
# > 什么值得买
^https?:\/\/api\.smzdm\.com\/v\d\/util\/loading - reject
# > 四季線上影視4gTV
^https?:\/\/service\.4gtv\.tv\/4gtv\/Data\/(GetAD|ADLog) - reject
# > 肆客足球
^https?:\/\/api\.qiuduoduo\.cn\/guideimage - reject
# > 识货
^https?:\/\/www\.shihuo\.cn\/app3\/saveAppInfo - reject
# > 首汽约车
^https?:\/\/gw-passenger\.01zhuanche\.com\/gw-passenger\/car-rest\/webservice\/passenger\/recommendADs - reject
^https?:\/\/gw-passenger\.01zhuanche\.com\/gw-passenger\/zhuanche-passenger-token\/leachtoken\/webservice\/homepage\/queryADs - reject
# > Suning
^https?:\/\/image\.suning\.cn\/uimg\/ma\/ad\/ - reject
# > 神舟专车
^https?:\/\/img01\.10101111cdn\.com\/adpos\/ - reject
# > SuperFriday
^https?:\/\/.+/V\d\/splash\/getSplashV\d\.action - reject

# T
# > Tencent
# >> Tencent Futubull
^https?:\/\/api5\.futunn\.com\/ad\/ - reject
# >> Tencent Game
^https?:\/\/ssl\.kohsocialapp\.qq\.com:10001\/game\/buttons - reject
^https?:\/\/qt\.qq\.com\/lua\/mengyou\/get_splash_screen_info - reject
# >> Tencent Maps
^https?:\/\/3gimg\.qq\.com\/tencentMapTouch\/app\/activity\/ - reject
^https?:\/\/3gimg\.qq\.com\/tencentMapTouch\/splash\/ - reject
^https?:\/\/4gimg\.map\.qq\.com\/mwaSplash\/ - reject
# >> Tencent QQLive
^https?:\/\/btrace.qq.com - reject
^https?:\/\/vv\.video\.qq\.com\/getvmind\? - reject
^https?:\/\/.+\.mp4.+&sdtfrom=v3004 - reject
# >> Tencent QQNews
^https?:\/\/r\.inews\.qq\.com\/(adsBlacklist|getFullScreenPic|getQQNewsRemoteConfig) - reject
# >> Tencent WeChat
^https?:\/\/mp\.weixin\.qq\.com\/mp\/(ad_|advertisement|getappmsgad) - reject
# > Thunder
^https?:\/\/images\.client\.vip\.xunlei\.com\/.+\/advert\/ - reject
# > TV_Home
^https?:\/\/api\.gaoqingdianshi\.com\/api\/v\d\/ad\/ - reject
# > The_Paper
^https?:\/\/adpai\.thepaper\.cn\/.+&ad= - reject
# > 太平洋
^https?:\/\/agent-count\.pconline\.com\.cn\/counter\/adAnalyse\/ - reject
^https?:\/\/mrobot\.pconline\.com\.cn\/v\d\/ad2p - reject
^https?:\/\/mrobot\.pconline\.com\.cn\/s\/onlineinfo\/ad\/ - reject
^https?:\/\/mrobot\.pcauto\.com\.cn\/v\d\/ad2p - reject
^https?:\/\/mrobot\.pcauto\.com\.cn\/xsp\/s\/auto\/info\/preload\.xsp - reject

# V
# > VUE
^https?:\/\/static\.vuevideo\.net\/styleAssets\/.+\/splash_ad - reject
^https?:\/\/static\.vuevideo\.net\/styleAssets\/advertisement\/ - reject

# W
# > WeDoctor
^https?:\/\/app\.wy\.guahao\.com\/json\/white\/dayquestion\/getpopad - reject
# > Weico
^https?:\/\/overseas\.weico\.cc/portal\.php\?a=get_coopen_ads - reject
# > 无他相机
^https?:\/\/api-release\.wuta-cam\.com\/ad_tree - reject
^https?:\/\/res-release\.wuta-cam\.com\/json\/ads_component_cache\.json - reject
# > 蜗牛睡眠
^https?:\/\/snailsleep\.net\/snail\/v\d\/screen\/qn\/get\? - reject
^https?:\/\/snailsleep\.net\/snail\/v\d\/adTask\/ - reject
# > WiFi共享大师
^https?:\/\/nochange\.ggsafe\.com\/ad\/ - reject
# > 微店
^https?:\/\/thor\.weidian\.com\/ares\/home\.splash\/ - reject
# > 华尔街见闻
^https?:\/\/api\.wallstreetcn\.com\/apiv\d\/advertising\/ - reject

# X
# > 下厨房
^https?:\/\/api\.xiachufang\.com\/v2\/ad/ - reject
# > 虾米
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alimusic\.common\.mobileservice\.startinit\/ - reject
# > 小睡眠
^https?:\/\/api\.psy-1\.com\/cosleep\/startup - reject
# > 迅游加速器
^https?:\/\/portal-xunyou\.qingcdn\.com\/api\/v\d\/ios\/configs\/(splash_ad|ad_urls) - reject
^https?:\/\/portal-xunyou\.qingcdn\.com\/api\/v\d\/ios\/ads\/ - reject
# > 喜马拉雅
^https?:\/\/.+\/api\/v\d\/adRealTime - reject
# > 小站
^https?:\/\/tiku\.zhan\.com\/Common\/newAd\/ - reject

# Y
# > Yahoo!
^https?:\/\/m\.yap\.yahoo\.com\/v18\/getAds\.do - reject
# > Youtube++
^https?:\/\/api\.catch\.gift\/api\/v3\/pagead\/ - reject
# > YOUKU
^https?:\/\/.+\.mp4\?ccode=0902 - reject
^https?:\/\/.+\.mp4\?sid= - reject
# > YYeTs
^https?:\/\/ctrl\.(playcvn|zmzapi)\.(com|net)\/app\/(ads|init) - reject
# > 萤石云视频
^https?:\/\/i\.ys7\.com\/api\/ads - reject
# > 运动世界
^https?:\/\/.+\.iydsj\.com\/api\/.+\/ad - reject
# > 一点万象
^https?:\/\/app\.mixcapp\.com\/mixc\/api\/v\d\/ad - reject
# > 印象笔记
^https?:\/\/app\.yinxiang\.com\/ads\/ - reject
# > 云麦好轻
^https?:\/\/restapi\.iyunmai\.com\/api\/ios\/ad\/ - reject
# > 育学园
^https?:\/\/yxyapi\d\.drcuiyutao\.com\/yxy-api-gateway\/api\/json\/advert\/ - reject

# Z
# > 直播吧
^https?:\/\/a\.qiumibao\.com\/activities\/config\.php - reject
^https?:\/\/.+\/allOne\.php\?ad_name - reject
# > 知乎
^https?:\/\/www\.zhihu\.com\/api\/v4\/community-ad\/ - reject
^https?:\/\/api\.zhihu\.com\/(launch|real_time) - reject
^https?:\/\/api\.zhihu\.com\/commercial_api\/(launch|real_time) - reject
# > 追书神器
^https?:\/\/(api|b)\.zhuishushenqi\.com\/advert - reject
^https?:\/\/api\.zhuishushenqi\.com\/splashes\/ios - reject
^https?:\/\/api\.zhuishushenqi\.com\/notification\/shelfMessage - reject
^https?:\/\/api\.zhuishushenqi\.com\/user\/bookshelf-updated - reject
^https?:\/\/itunes\.apple\.com\/lookup\?id=575826903 - reject
# > 作业帮
^https?:\/\/www\.zybang\.com\/adx\/ - reject
# > 最右
^https?:\/\/api\.izuiyou\.com\/ad\/ - reject
