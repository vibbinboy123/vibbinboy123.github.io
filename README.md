# vibbinboy123.github.io
css
/*ando fixes start*/

.rainbowText{background-image: linear-gradient(to right, #2e62ff, #0099ff , #00ff00, #ffde3b, #ff3399, #6666ff);animation: gradient-border 2s linear infinite;background-size: 400% 100%;color: transparent !important;-webkit-background-clip: text;}
@keyframes gradient-border{0%, 200% {background-position: 0 0;}99.999999999999999% {background-position: -130% 0;}} 


*::-webkit-scrollbar {
    display: none;
}



.button, .menuItem, #mapInfo {
    text-transform: lowercase;
}

.menuItemTitle {
	color: var(--accent) !important;
}

.menuItem:hover > .menuItemTitle {
    color: white !important;
}

#hostMenuBtn {
	display: none !important;
}

#hideFull {
	position: absolute !important;
    right: 25px !important;
}

.changeText {
	color: var(--accent);
}

.vis-item {
	background-color: var(--accent) !important;
	border-color: black !important;
}

.vis-text {
	color: var(--accent) !important;
}

#premTime {
    color: var(--accent);
}

#creatorDash > div > span {
	color: var(--accent) !important;
}

#creatorDash > div > span > span {
	color: var(--accent) !important;
}


.altlistelement {
	color: rgba(255,255,255,0.75) !important;
	box-shadow: none !important;
	background-color: transparent !important;
}
.altdeletebtn {
	box-shadow:none !important;
	background-color: transparent !important;
	color: red !important;
}

#shareTxt {
	color: black !important;
}

.menuDebugInfo {
	display: block !important;
}

#menuFPS, #menuPingText, #menuPingIcon {
	color: var(--accent) !important;
}

#headerRight > .verticalSeparator {
	display:none !important;
}

#menuPingDisplay, #menuFPSDisplay, #menuPingText, #menuFPS {
    font-size: 16px;
}

#menuFPSDisplay {
    margin-right: 0px;
}

#menuRegionLabel {
    text-transform: lowercase;
}

#menuPingDisplay {
	position: fixed;
    right: 10px;
}

[style$="background-color:gainsboro;border-radius:6px;padding:5px"] {
	background-color:transparent !important;
}

.mailText, .mailObj, #mailList {
	color: var(--accent) !important;
}

.setHed > div {
	color: var(--accent) !important;
}


#clientExitPop {
	background-color: rgba(0,0,0,0.4) !important;
    box-shadow: 0 0 8px 2px var(--accent) !important;
    border-radius: 12px !important;
	top: 85%;
}

#consentWindow {
	background-color: rgba(0,0,0,0.4) !important;
    box-shadow: 0 0 8px 2px var(--accent) !important;
    border-radius: 12px !important;
}

#clientExitPop > div {
	text-align: center;
}

#confirmBtn, #declineBtn,.termsBtn {
	text-shadow:none !important;
	color:black;
}

#krRewardsInfo > div > div > span {
	color: var(--accent) !important;
}


#ingameFPS {
    color: var(--accent-color) !important;
}

#pingIcon {
    color: var(--accent) !important;
}

#jumpSIMG, #jumpSVIDHolder {
	display:none !important;
}


.countIcon {
    background-color: rgba(0,0,0,0) !important;
    border-radius: 0;
    margin-left: 20px;
	text-shadow: none !important;
    margin-bottom: 0;
    padding: 7px;
}


.slidecontainer {
    margin-top: 5px;
}




#leaderDisplay {
    background-color: rgba(0,0,0,0.2) !important;
}



#killStreakHolder {
    position: fixed;
    right: 48.54%;
    bottom: 10px;
    margin-right: 0px;
    margin-bottom: 0px;
}

.killStreakItem {
	background-color: transparent;
}

#itemSearch {
	background-color: transparent;
	box-shadow: 0 0 8px 2px var(--accent);
}
#polConfPop {
	background-color: black;
    box-shadow: 0 0 8px 2px var(--accent);
    border-radius: 12px;
}

#polConfPop > div {
	color: var(--accent) !important;
}

#polConfPop > #confirmBtn, #polConfPop > #declineBtn{
	text-shadow:none !important;
	color:black !important;
}

#tradeChatHolder {
	bottom: 376px;
}
#tradeChatInput {
	border-radius: 4px;
	font-size: 14px;
}

#tradeChatList {
	max-height: 520px;
	overflow-y: auto;
}

.tradeChatItem {
	font-size: 14px;
}

.tListN.inv {
	background-color: var(--accent) !important;
}

#tSubName, #tDecName {
	text-shadow:none;
	color:black;
}

.estOfferVal {
	color: gray;
}

.estOfferVal > span {
	color: var(--accent) !important;
}

#interactMsg {
    bottom: 270px;
}

#interactMsg > span {
    color: var(--accent) !important;
}

.tItemN {
	font-size: 10px;
	text-align: center;
}

.tTotal {
	color: black;
}

.material-icons.vote {
    color: var(--accent);
}
.meleeChatIcon {
	filter: brightness(0) drop-shadow(-2px 0px 1px #fff) drop-shadow(0px 0px 1px #fff) drop-shadow(2px 0px 1px var(--accent));
}

/*ando fixes end*/





/*Section I: Frame*/

:root {
    --accent: #ffcd36;
}

/*DO NOT EDIT BELOW UNLESS YOU KNOW WHAT YOU ARE DOING*/

@font-face {
    font-family: gamefont;
    src: url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLBT5Z1xlFQ.woff2);
}

* {
    color: #fff;
}

a {
    color: var(--accent);
}

.grey {
    color: rgba(255,255,255,.5);
}

.material-icons[style*="color:#FBC02D"] {
    color: var(--accent) !important;
}

.material-icons[style*="color:#40C4FF"] {
    color: var(--accent) !important;
}

.material-icons[style*="color:#2196F3;font-size:33px;vertical-align:bottom;"] {
    color: var(--accent) !important;
}

/*You Hate to See It*/

#aHolder {
    display: none !important;
}

.endAHolder {
    display: none !important;
}

#onetrust-consent-sdk {
    display: none;
}

#newsHolder {
    display: none;
}

.krSocial {
    display: none;
}

.imageButton, #editorBtnM {
    display: none !important;
}

/*Section II: Chat*/

#uiBase.onMenu #chatHolder {
    left: 20px;
}

#chatHolder[style="bottom: 148px;"] {
    bottom: 30px !important;
}

#chatList {
    text-align: center;
}

#chatList::-webkit-scrollbar {
    width: 4px;
}


#chatList::-webkit-scrollbar-thumb {
    background: var(--accent);
    border-radius: 50px;
}

#chatList::-webkit-scrollbar-track {
  background: transparent;
}

#chatInput {
    text-align: center;
}

.chatItem {
    color: #fff !important;
    font-size: 16px;
    width: -webkit-fill-available;
    box-shadow: rgba(255, 255, 255, 0.25) 0px 0px 0px 2px inset;
    margin: 0px;
    background-color: rgba(0,0,0,0.4) !important;
    border-radius: 0;
}


.weaponChatIcon {
    filter: brightness(0) drop-shadow(-2px 0px 1px #fff) drop-shadow(0px 0px 1px #fff) drop-shadow(2px 0px 1px var(--accent));
}

.chatMsg[style*="#ffffff"] {
    color: #fff !important;
}

.chatMsg span {
	color: var(--accent) !important;
    opacity: 0.75;
}

.chatMsg span[style="color:#9eeb56"] {
    color: #ffffff !important;
}

.chatMsg span[style="color:#fff"] {
    color: #ffffff !important;
}

#chatInput {
    text-align: center;
    background-color: transparent;
    border-bottom: 4px solid var(--accent);
}

#voiceDisplay {
    display: none;
}

/*Section III: Menu*/

#mainLogo {
    content: url(https://cdn.discordapp.com/attachments/819588051500007454/835924834777169950/Lucidwhitenobg.png);
}

#gameNameHolder:hover #mainLogo {
    /*content: url(https://cdn.discordapp.com/attachments/570906904713363457/806408830098997288/timp.gif);*/
}

#gameNameHolder {
    pointer-events: all;
    font-size: 0;
    color: transparent;
    transition: 0.5s;
}

#gameNameHolder:hover {
    font-size: 36px;
    color: #fff;
}

#gameNameHolder::after {
    content: "css by tae#4444, edited by ominous#7150";
    display: block;
    font-family: 'ISOCP';
}

#seasonLabel {
    display: none;
}

.onMenu #instructions {
    display: none;
}

#instructionsUpdate {
    background-color: rgba(0,0,0,0.4);
    box-shadow: 0 0 8px 2px var(--accent);
}

/*Headers*/

.headerBar {
    background-color: transparent;
}

#mailIcon {
    font-size: 32px !important;
}

#mLevelCont {
    position: relative;
    left: 0px !important;
    font-size: 16px;
    line-height: unset;
    height: unset;
    padding: 0 4px;
    margin-left: 8px;
    border-radius: 4px;
}

.progressBar {
    background-color: rgba(255,255,255,0.15);
    padding: 0;
}

.progressBarInner {
    background-color: var(--accent);
}

.verticalSeparator {
    height: 4px !important;
    border-width: 0;
    background-color: var(--accent);
}

#tlInfHold {
    left: 20px;
}

#youNewDiv {
    display: none;
}

#streamContainer {
    left: 20px;
    height: 32px;
    padding: 0;
    overflow: hidden;
    background-color: transparent;
    transition-duration: 0.5s;
}

#streamContainer:hover {
    height: 400px;
}

.streamItem[style="text-align: center;"] {
    text-align: left !important;
}

.menuDebugInfo {
    display: none;
}

#uiBase.onMenu #spectButton {
    z-index: 1;
    width: 96px;
    top: 50%;
}

#spectButton span[style="font-size:15px;color:rgba(255,255,255,0.6)"] {
    color: transparent !important;
}

#spectButton .switchsml {
    margin: 0;
    position: absolute;
    width: 100%;
}

.sliderSml {
    opacity: 1;
}

.sliderSml::before {
    content: "Spectate";
    font-size: 20px;
    color: white;
    width: max-content;
    height: auto;
    background-color: transparent;
    text-align: center;
    transition-duration: 0.25s;
}

input:checked+.sliderSml::before {
    content: "Spectating";
    transform: translateX(-12px);
    color: var(--accent);
}
input:checked+.sliderSml {
    background-color: transparent !important;
}

.sliderSml {
    opacity: 1;
    background-color: transparent;
}

/*Menu Buttons*/

#subLogoButtons {
    bottom: 72px;
    transform: translate(-50%,0);
}

#subLogoButtons>.button {
    padding: 0 !important;
    margin: 0 16px;
    background-color: transparent !important;
    box-shadow: none !important;
    text-shadow: none !important;
    font-size: 24px !important;
    transition-duration: 0.25s;
}

#subLogoButtons>.button:hover {
    transform: unset;
    color: var(--accent);
}

#menuItemContainer {
    flex-direction: row;
    top: unset;
    bottom: 20px;
    left: 50%;
    width: unset;
    transform: translateX(-50%)
}

.menuItem {
    background-color: transparent;
    margin: 0 16px;
}

.menuItem:hover {
    border-left: none;
}

.menuItem .menuItemIcon {
    display: none;
}

.menuItem .menuItemTitle {
    margin: 0;
    font-size: 24px !important;
    transition-duration: 0.25s;
}

.menuItem:hover> .menuItemTitle {
    color: var(--accent);
}

/*Menu Window*/

#menuWindow::-webkit-scrollbar {
    width: 2px;
}

#menuWindow::-webkit-scrollbar-thumb {
    background: var(--accent);
    border-radius: 50px;
}

#menuWindow::-webkit-scrollbar-track {
  background: transparent;
}

#menuWindow {
    background-color: rgba(0,0,0,0.4);
    box-shadow: 0 0 8px 2px var(--accent);
    border-radius: 12px;
}

.settName, .settNameSmall {
    color: rgba(255,255,255,0.75);
}

.settName.b {
    color: var(--accent) !important;
}

#menuWindow div[style="color:rgba(0,0,0,0.3);margin-top:-5px;margin-bottom:10px"] {
    display: none;
}

#menuWindow [style*="rgba(0,0,0,0.3)"], #menuWindow [style*="rgba(0,0,0,0.4)"], #menuWindow [style*="rgba(0,0,0,0.5)"], #menuWindow [style*="rgba(0,0,0,0.8)"]  {
    color: rgba(255,255,255,0.5) !important;
}

#menuWindow [style*="#000"] {
    color: #fff !important;
}

#menuWindow [style="color:#2196F3"] {
    color: var(--accent) !important;
}

#menuWindow .settText[style*="#292929"], #menuWindow .wepLink[style*="#292929"] {
    filter: drop-shadow(0px 0px 2px var(--accent)) drop-shadow(0px 0px 4px var(--accent));
}

.floatR span[style="color:rgba(0,0,0,0.5)"] {
    color: var(--accent) !important;
}

.menuTabNew {
    color: #fff;
}

.xpBar {
    background-color: rgba(255,255,255,0.15);
    border-radius: 12px;
    height: 24px;
    padding: 0;
}

.xpBarB {
    border-radius: 12px;
    background-color: var(--accent);
}

.xpBarV {
    top: 0px;
}

/*Account & Login*/

.accountInput {
    color: #fff;
}

.accountButton {
    background-color: transparent;
    color: var(--accent);
    transition-duration: 0.25s;
}

.button.lgn {
    width: auto !important;
    padding: 0 !important;
    margin: 0 !important;
    box-shadow: none !important;
    background-color: transparent !important;
    text-shadow: none !important;
    color: var(--accent);
}

/*Clan Page*/

#clanWarKPB {
    background-color: var(--accent);
}

#clanFundsIn {
    background-color: transparent;
    border: none;
}

.clanFndB {
    background-color: transparent !important;
    color: var(--accent);
}

/*Shop*/

#limitedBarProg {
    background-color: var(--accent);
}

/*Challenges*/

.chalCard {
    text-shadow: none;
}

.chalXPBar {
    padding: 0;
    border-radius: 12px;
    background-color: rgba(255,255,255,0.15);
}

.chalXPBarC {
    border-radius: 12px;
    background-color: var(--accent);
}

.chalImgC {
    background-color: transparent;
    filter: grayscale(1) brightness(2) drop-shadow(0px 0px 2px var(--accent)) drop-shadow(0px 0px 4px var(--accent));
}

/*Customization*/

#menuClassContainer {
    transform: unset;
}

#menuClassNameTag {
    display: none;
}

#bubbleContainer {
    display: none;
}

#menuClassName, #menuClassSubtext {
    text-shadow: none;
}

#menuClassName {
    font-size: 28px;
}

#menuClassSubtext {
    color: var(--accent);
}

#customizeButton {
    width: 300px;
    height: 300px;
    position: fixed;
    right: 80px;
    bottom: 50%;
    transform: translateY(75%);
    font-size: 0 !important;
    background-color: transparent !important;
    box-shadow: none !important;
}

#customizeButton .material-icons {
    display: none;
}

/*Loadout*/

#loadoutSelect {
    background-color: rgba(255,255,255,0.15) !important;
    border-radius: 16px !important;
}

#loadoutName {
    background-color: transparent !important;
    border-radius: 0;
    border-bottom: 4px solid var(--accent) !important;
}

.settText, .wepLink {
    color: var(--accent);
}

.wepLink[style="color:#2196F3"] {
    color: var(--accent) !important;
}

.skinColorItem {
    width: 24px;
    height: 24px;
    border: none;
}

.premiumSkinCol {
    font-size: 28px !important;
    margin-top: -2px;
    color: var(--accent) !important;
}

/*Class and Skin Card*/

.classCard {
    text-shadow: none;
    background-color: rgba(255,255,255,0.15);
    border-radius: 8px;
    height: 228px;
    line-height: 28px;
    font-size: 0;
    transition-duration: 0.25s;
}

.classCard:hover {
    font-size: 28px;
    background-color: rgba(0,0,0,0.4);
}

.classWeap {
    font-size: 0;
    height: 0;
}

.classImgC {
    margin-top: 12px;
    transition-duration: 0.25s;
}

.classCard:hover img {
    opacity: unset;
    transform: unset;
}

.classXPBar {
    top: unset;
    bottom: 0;
    width: -webkit-fill-available;
    left: -0;
    height: 4px;
    background-color: rgba(0,0,0,0.25);
}

.clsXPBarC {
    margin: 0;
    height: 4px;
    background-color: var(--accent);
}

.skinCard[style*="#292929"], .noBtnCard[style*="#292929"] {
    text-shadow: 0 0 2px var(--accent), 0 0 4px var(--accent);
}

.skinCard, .noBtnCard {
    border-radius: 8px;
    border-width: 0 !important;
    border-bottom-width: 4px !important;
    background-color: rgba(255,255,255,0.15);
    width: 155px;
    margin-left: 5px;
    margin-right: 5px;
}

.skinCard.blackShad {
    text-shadow: none;
}

.noBtnCard {
    width: 145px;
}

.sprayImg {
    margin-left: 20px;
}

/*KPD*/

#policeButton {
    margin: 0;
    padding: 0;
    height: 40px !important;
    width: 58px !important;
    color: #fff;
    display: block;
    position: fixed;
    bottom: 20px;
    left: 320px;
    background-color: transparent !important;
    box-shadow: none !important;
    background-image: url(https://cdn.discordapp.com/attachments/819588051500007454/835924834777169950/Lucidwhitenobg.png);
    background-size: cover;
}

#policeButton img {
    margin: 0 !important;
    height: 36px !important;
    opacity: 0;
}

#policePopC {
    background-color: rgba(44,44,44);
    box-shadow: 0 0 8px 2px var(--accent);
}

#policePopC [style*="0.6"] {
    color: rgba(255,255,255,0.5) !important;
}

#trustProg {
    padding: 0;
    border-radius: 14px;
    height: 28px;
    background-color: rgba(255,255,255,0.15);
}

#trustPrgHD {
    height: 100%;
    border-radius: 14px;
    background-color: var(--accent) !important;
}

#trustProgHD {
    text-shadow: none;
    line-height: 32px;
    font-size: 20px;
}

#activateKDM {
    width: auto;
    background-color: transparent !important;
    color: var(--accent);
    text-shadow: none !important;
    box-shadow: none !important;
}

/*Mod and Map List*/

#mpCat, .searchBtn {
    background-color: rgba(255,255,255,0.15);
    border-radius: 16px;
    border: none;
}

.mapByTxt {
    color: #fff;
}

/*Map Host*/

.hostMap {
    border: none;
    height: 94px;
    width: 230px;
}

.hostMapBy, .hostMapYear, .hostMapVersion {
    display: none;
}

.hostMapName {
    top: 50%;
    left: 50%;
    font-size: 24px;
    width: 100%;
    text-align: center;
    transform: translate(-50%, -50%);
}

.hostMapImg {
    filter: grayscale(100%) brightness(0.75);
    border-radius: 8px;
    width: 230px;
}

.hostMap .blackShad {
    text-shadow: none;
}

.hostOpt {
    border: none;
    border-radius: 24px;
    background-color: transparent;
    width: 210px;
}

.optName {
    text-shadow: none;
    font-size: 20px;
    width: 100%;
    display: flex;
    justify-content: center;
}

.optCheck {
    background-color: transparent;
    border-radius: 24px;
}

input:hover+.optCheck {
    background-color: var(--accent);
    opacity: 0.25;
}

input:checked+.optCheck {
    background: transparent;
    box-shadow: inset 0 0 16px 2px var(--accent);
}

#customSnameTeam1, #customSnameTeam2, #passCode, #rawMapData, #presetName, #presetSelect {
    border-radius: 6px !important;
    background-color: rgba(255, 255, 255, 0.15) !important;
}

/*Options/Settings*/

.serverHeader, .settingsHeader {
    background-color: transparent;
    position: static;
}

#settSearch {
    border-radius: 0;
    background-color: transparent;
    border-bottom: 4px solid var(--accent);
}

.settingTab {
    grid-row: 1;
}

.settingTab, .tabANew {
    grid-row: 1;
    border-color: var(--accent);
    transition-duration: 0.25s;
}

.settingTab:hover, .tabANew:hover, .menuTabNew:hover {
    border-color: var(--accent);
    opacity: 0.75;
}

.settingsBtn, .loadoutBtn, .subPassChg, .lnkTw, .hostToggle, .hostPresetBtn {
    background-color: rgba(255,255,255,0.15);
    color: #fff;
    border-radius: 16px;
}

.lnkTw {
    color: var(--accent);
}

.inputGrey, .inputGrey2, .formInput {
    background: rgba(255,255,255,0.15);
    border-radius: 16px;
}

.smlInput {
    color: #fff;
}

option {
    background: #000;
}

.setHed {
    color: var(--accent);
}

.plusOrMinus {
    font-size: 36px !important;
    margin-right: -4px !important;
    color: var(--accent);
}

.settName span[style="color: #eb5656"] {
    color: var(--accent) !important;
}

#requiresRestart {
    color: var(--accent);
}

#requiresRestart span {
    color: var(--accent) !important;
}

.sliderM {
    height: 8px;
    position: relative;
    top: -4px;
    background-color: rgba(255, 255, 255, 0.15);
}

.sliderM::-webkit-slider-thumb {
    background-color: transparent;
    width: 16px;
    height: 16px;
    border-radius: 50%;
    box-shadow: inset 0 0 0 4px var(--accent);
}

.sliderVal {
    background-color: rgba(255,255,255,0.15);
    color: #fff;
    border-radius: 16px;
}

.switch {
    width: 70px;
}

.slider {
    background-color: rgba(255,255,255,0.15);
    border-radius: 16px;
}

input:checked+.slider {
    background-color: var(--accent);
}

.slider:before {
    background-color: transparent;
    content: "ー";
    font-weight: bolder;
    -webkit-text-stroke: medium;
    text-align: center;
    font-size: 16px;
    transition: .25s;
    border-radius: 16px;
}

input:checked+.slider:before {
    transform: translateX(36px) rotate(360deg);
    color: transparent;
    box-shadow: inset 0 0 0 4px #fff;
}

.switch2 {
    width: 48px;
}

.slider2 {
    background-color: rgba(255,255,255,0.15);
    border-radius: 16px;
}

input:checked+.slider2 {
    background-color: var(--accent);
}

.slider2:before {
    background-color: transparent;
    content: "ー";
    font-weight: bolder;
    -webkit-text-stroke: medium;
    text-align: center;
    font-size: 14px;
    transition: .25s;
    border-radius: 16px;
}

input:checked+.slider2:before {
    transform: translateX(16px) rotate(360deg);
    color: transparent;
    box-shadow: inset 0 0 0 4px #fff;
}

input[type=color] {
    width: 60px;
    border-color: var(--accent);
}

/*Server Nav*/

.menuSelectorHeader {
    width: 796px;
}

.quickJoin {
    background-color: transparent;
    color: var(--accent);
    font-size: 16px;
    padding: 0;
    margin-bottom: 4px;
    margin-left: 12px;
}

.slide {
    border-color: transparent;
}

#menuWindow [style*="rgba(0,0,0,0.6)"] {
    color: #fff !important;
}

/*Terms Area*/

#mapInfo {
    margin-bottom: 0px;
}

#termsInfo {
    background-color: transparent;
}

.verticalSeparatorInline {
    height: 40px;
}

.terms {
    font-size: 0;
    transition-duration: 0.25s;
}

.terms:last-child {
    font-size: 20px;
}

#termsInfo:hover .terms {
    font-size: 20px;
}

.verticalSeparatorInline {
    width: 0;
    height: 36px;
    opacity: 0;
    transition-duration: 0.25s;
}

#termsInfo:hover .verticalSeparatorInline {
    width: 4px;
    opacity: 1;
}

.standout::before {
    content: 'twitch.tv/lucidexists';
    font-size: 20px;
    margin-right: 20px;
    color: rgba(255, 255, 255, .5);
    visibility: visible;
    pointer-events: none;
}

/*Section IV: HUD*/

/*Health*/

#hudClassIcon {
    display: none;
}

#healthValueHolder {
    background-color: transparent;
    padding: 0 !important;
    margin: 0 !important;
    bottom: 20%;
    right: 62.5%;
    transform: translateX(50%);
    position: fixed;
}

#healthValue {
    font-size: 64px !important;
	text-shadow: 2px 2px 4px #000;
}

#maxHP {
    display: none;
}

#healthBar {
    display: none;
}
 
.hpBSeg, .healthBarSeg {
    display: none;
}

#challIcon {
    display: none !important;
}

/*Ammo*/




#ammoDisplay {
    background-color: transparent !important;
    background-image: linear-gradient(90deg, var(--accent), var(--accent));
    background-position-y: 92px;
    border-radius: 0px;
    padding: 0;
    padding-bottom: 32px;
    padding-top: 0;
    padding-left: 0;
    padding-right: 0 !important;
    position: fixed;
    bottom:20%;
    left: 62.5%;
    justify-content: center;
    text-align: center;
    transform: translateX(-50%);
}

#ammoVal {
    font-size: 64px;
    color: var(--accent);
    text-shadow: 2px 2px 0px #000 !important;
}

#ammoMax {
    display: none;
}

#ammoIcon {
    display: none !important;
}

#reloadMsg {
    background: none;
    color: var(--accent);
}

/*Weapon Display*/

#weapDisplay {
    bottom: 30px;
}

.weapItem {
    position: absolute;
    bottom: 0;
    right: 0;
}

.weapIcon {
    filter: brightness(0) drop-shadow(-2px 0px 1px #fff) drop-shadow(0px 0px 1px #fff) drop-shadow(2px 0px 1px var(--accent));
    opacity: 0 !important;
    transition-duration: 0.25s;
    height: 0;
}

.weapIcon[style*="1"] {
    opacity: 1 !important;
    height: 70px;
}

#weapIconMel {
    margin: 0 !important;
}

.weapKey {
    display: none;
}

/*Top Left*/

#pingDisplay .material-icons, #ingressDisplay .material-icons, #egressDisplay .material-icons {
    font-size: 24px;
}

#pingIcon {
    color: var(--accent) !important;
}

#timerDisplay {
    position: fixed;
    left: 50%;
    bottom: 15%;
    transform: translateX(-50%);
    background-color: transparent;
}

#timerVal {
    text-shadow: 2px 2px 4px #000;
}

#timerIcon {
    display: none;
}

/*Top Right*/

#streakCount {
    position: fixed;
    left: 50%;
    bottom: 10%;
    background-color: transparent;
    transform: translate(-50%);
}

.countIcon {
    background-color: transparent;
    color: #fff;
    text-shadow: 2px 2px 4px #000;
    font-size: 32px;
}

#killsIcon, #deathsIcon, #streakIcon, #kdIcon {
    width: 28px;
    height: 28px;
}

#killsVal, #deathsVal, #streakVal, #myScoreVal, #kdVal {
    color: #fff;
}

/*Leaderboard*/

#leaderDisplay::before {
    content: "leaderboard";
    display: flex;
    font-size: 24px;
    color: #fff;
    border-bottom: 4px solid var(--accent);
    border-image-slice: 1;
    margin-bottom: 8px;
    padding-bottom: 4px;
}

#leaderDisplay {
    background-color: transparent;
}

.leaderName, .newLeaderName, .newLeaderNameF, .endTableN[style*="color:#eb5656"] {
    color: var(--accent) !important;
}

/*End Card*/

#victorySub {
    display: none;
}

.teamTotals {
    background-color: transparent;
}

.teamTotalN0 {
    color: rgba(44,44,44);
    text-shadow: 0 0 4px var(--accent), 0 0 4px var(--accent);
}

.teamTotalN1 {
    color: var(--accent);
    text-shadow: 0 0 4px var(--accent), 0 0 4px var(--accent);
}


.teamTotalScore, .teamTotalN0, .teamTotalN1 {
    font-size: 24px;
}

#matchVoteHolder {
    background-color: transparent;
}

.matchVote {
    transition-duration: 0.25s;
}

.matchVote:hover {
    box-shadow: 0 0 8px 2px var(--accent);
}

.matchVoteThumb:hover {
    opacity: unset;
    transform: unset;
}

.endCard {
    border-radius: 12px;
    background-color: rgba(0,0,0,0.4);
    box-shadow: 0 0 8px 2px var(--accent);
}

.tabHeader.selected {
    color: var(--accent);
    border-color: var(--accent);
}

.reportBut {
    color: var(--accent);
}

#endTable span[style="color:#F8C55C"] {
    color: var(--accent) !important;
}

/*Spectate*/

#specNames, #specContr {
    background-color: transparent;
    text-shadow: 2px 2px #000;
}
