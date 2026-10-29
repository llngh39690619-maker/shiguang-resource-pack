JsonItems｜自訂物品與穿戴外觀獨立資源包

適用 Minecraft Java Edition 26.2，資源包格式 88。
包含星晶長劍、紫晶羽翼、星晶護翼的示範外觀：兩個原創靜態 Java 模型、三個 item_model 定義及透明裝備圖層。模型引用遊戲內建方塊貼圖；資源包不包含遊戲原始貼圖。

公開下載：
https://raw.githubusercontent.com/llngh39690619-maker/shiguang-resource-pack/main/jsonitems/jsonitems-1.0.0.zip
SHA1：04438fbc431eb17079afaf1cae0821f8eff17e5f
SHA256：60ccef66c36fee8daebc00aa6a30be19686314324e77c66f5ae3f6fc31748783

這份 ZIP 與 fishing/ 魚類資源包分開，能由伺服器一起疊加。
ZIP 僅提供外觀；物品發放、胸部穿戴模型、防護模式及滑翔開關由 JsonItems 插件處理。
單獨下載 ZIP 不會自動給予物品或新增飛行功能。

搭配 JsonItems：
/ji pack：重新請求資源包。
/ji give demo_sword：鑽石劍功能與自訂外觀。
/ji give demo_wings：純裝飾翅膀，預設沒有防護與滑翔。
/ji give demo_armor：翅膀外觀，保留鑽石胸甲防護。
/ji glide demo_wings on 或 off：管理員切換新領取羽翼的滑翔能力。
/ji updatehand：用目前設定更新主手的舊物品。

管理員日後增加模型或新 item_model 定義時，須重新建包、發布新 ZIP，並同步更新插件設定中的下載網址。此公開包不會自動包含其他伺服器自行匯入的素材。
公開目錄不含插件 JAR、私人設定、帳密、玩家資料或經濟資料庫。
