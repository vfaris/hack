<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
    <head profile="http://www.w3.org/2005/10/profile">
        <!--C9LOCAL_CODE_INJECT_PLACEHOLDER-(login-head)-DO_NOT_REMOVE-->
        <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
        <title>Sign-in | Cloud9 IDE - Ajax.org</title>
        <meta name="description" content="Meet Cloud9, development-as-a-service for Javascripters and other developers"/>
        <meta name="keywords" content=""/>

        <link rel="icon" type="image/gif" href="https://static.c9.io/nc-3.1.3412-3ebb4f73/static/homepage/favicon.ico" />

        <!--C9LOCAL_CODE_INJECT_PLACEHOLDER-(login-loadedDetectionScript)-DO_NOT_REMOVE-->
        <link href="https://static.c9.io/nc-3.1.3412-3ebb4f73/static/oldclient/homepage/style/signin.css" rel="stylesheet" type="text/css" />
        <script type="text/javascript" src="https://static.c9.io/nc-3.1.3412-3ebb4f73/static/oldclient/homepage/js/prefixfree.min.js"></script>
    </head>
    <body class="">
        <script type="text/javascript">
            // ClickTale Top part
            var WRInitTime=(new Date()).getTime();
            // ClickTale end of Top part
        </script>
        <div id="header">
            <a class="logo" href="/"></a>
            <div class="social">
                <div class="socialMediaBlok">
                    <a href="http://twitter.com/share" class="twitter-share-button" data-url="http://c9.io/" data-text="Cloud9 IDE - Your code anywhere, anytime" data-count="horizontal" data-via="cloud9ide">Tweet</a>
                    <script type="text/javascript" src="//platform.twitter.com/widgets.js"></script>
                </div>
                <div class="socialMediaBlok">
                    <iframe src="//www.facebook.com/plugins/like.php?href=c9.io&amp;layout=button_count&amp;show_faces=false&amp;width=90&amp;action=like&amp;font=lucida+grande&amp;colorscheme=light&amp;height=21"
                      allowtransparency="true"
                      scrolling="no"
                      frameborder="0"
                      style="border:none; overflow:hidden;height:20px"></iframe>
                </div>
            </div>
        </div>
        <div class="headerdivider"></div>
        <div id="signin_window">
            <div id="signinViewport">
                <div class="pageContainer">
                    <div id="barForgetPass" class="page">
                        <form id="resetPasswordForm">
                            <div class="header">Reset password</div>
                            <div class="form-holder">
                                <div id="lbl_inpResetPassword" class="c9-label">
                                    <label for="inpResetPassword">Username or email address</label>
                                </div>
                                <div class="c9-textbox">
                                    <div class="c9-txt_fix">
                                        <input type="text" id="inpResetPassword" name="inpResetPassword" disabled2="disabled" />
                                    </div>
                                </div>
                            </div>
                        </form>

                        <div class="fbox">
                            <div id="btnRPCancel" class="cancel-button button">Go back</div>
                            <div id="btnRP" class="action-button button">Reset my password</div>
                        </div>
                        <div class="label3">Your password will be reset and you will receive an email with a new password.</div>
                    </div>
                    <div id="barSignIn" class="page">
                        <form id="signinForm">
                            <div class="header">Please sign in</div>
                            <div class="form-holder">
                                <div id="lbl_inpUsernameEmail" class="c9-label">
                                    <label for="inpUsernameEmail">Username or email address</label>
                                </div>
                                <div id="txt_inpUsernameEmail" class="c9-textbox">
                                    <div class="c9-txt_fix">
                                        <input type="text" id="inpUsernameEmail" name="inpUsernameEmail" tabindex="1" />
                                    </div>
                                </div>
                                <div id="lbl_inpPassword" class="c9-label">
                                    <label for="inpPassword">Password</label>
                                    <a id="forgetlink" class="forgetlink">Forgot?</a>
                                </div>
                                <div id="txt_inpPassword" class="c9-textbox">
                                    <div class="c9-txt_fix">
                                        <input type="password" id="inpPassword" name="inpPassword" tabindex="2" />
                                    </div>
                                </div>

                                <div class="fbox">
                                    <div id="cbRememberLogin" class="c9-checkbox" tabindex="3">
                                        <div class="check"></div><span>Remember my login</span>
                                    </div>
                                    <div id="btnSignIn" class="action-button button" tabindex="4"  accesskey="ENTER">Sign in</div>
                                </div>
                            </div>
                            <div id="barSignInStatusMsg" class="signinstatus-bar">
                                <div id="lblSignInHeader" class="errorboxContent"></div>
                                <div id="lblSignInStatus" class="errorboxContent"></div>
                            </div>
                        </form>
<!--                        <div id="btnLoginViaGitHub" class="c9-button btn-github" style="margin: 13px 0 0 12px;" tabindex="5"></div>-->
                        <div class="signin_options">
                            <div class='info'>Or sign in with:</div>
<!--                            <a href="#" class="c9-button google-signin" tabindex="8"></a>
                            <a href="#" class="c9-button twitter-signin" tabindex="7"></a>
                            <a href="#" class="c9-button facebook-signin" tabindex="6"></a>-->
                            <a href="#" class="c9-button github-signin"></a>
                            <a href="#" class="c9-button bitbucket-signin"></a>
                        </div>
                    </div>
                    <div id="barActivationLink" class="page">
                            <form id="activationlinkForm">
                                <div class="header">Activation email</div>
                                <div class="form-holder">
                                    <div id="lbl_inpResetPassword" class="c9-label">
                                        <label for="inpResetPassword">Username or email address</label>
                                    </div>
                                    <div class="c9-textbox">
                                        <div class="c9-txt_fix">
                                            <input type="text" id="inpResendConfirmation" name="inpResendConfirmation" />
                                        </div>
                                    </div>
                                </div>
                            </form>
                            
                            <div class="fbox">
                                <div id="btnALCancel" class="cancel-button button">Go back</div>
                                <div id="btnAL" class="action-button button">Resend activation email</div>
                            </div>
                            <!--div style="clear: both"></div-->
                        <!--div class="divider" style="margin:40px 5px 0 5px;"></div>
                        <div class="label3" style="margin:21px 17px 0 17px;">To receive the registration email again please click the button above.</div-->
                    </div>
                </div>
            </div>
        </div>
        <div id="signup_window">
            <div class="no_account_yet"></div>
            <div class="signuplink-bar">
                <div class="bird"></div>
                <div class="content">
                    <a id="btnSignUpUrl" href="/signup">SIGN UP</a> FOR YOUR ACCOUNT
                </div>
            </div>
        </div>
<!--        <div id="terms_of_use">
            <a href="#">Terms of use</a> - &#169; 2011 - <a href="/">Register here</a>
        </div>-->
        <div class="sign_up_now">
            <a id="resendactivation">Resend my activation email</a>
        </div>
        

        <ul class="bottom_menu">
            <li><a href="/" class="selected">Home</a></li>
            <li>|</li>
            <li>Talk to us at <a href="http://twitter.com/cloud9ide/" target="_blank">Twitter</a> and <a href="http://www.facebook.com/Cloud9IDE/" target="_blank">Facebook</a></li>
<!--            <li>|</li>-->
<!--            <li><a href="#">Terms of use</a></li>-->
            <li>|</li>
            <li>Cloud9 IDE, Inc &#169; 2011</li>
        </ul>

        <script type="text/javascript" src="https://static.c9.io/nc-3.1.3412-3ebb4f73/static/oldclient/homepage/js/jquery-1.5.1.min.js"></script>
        <script type="text/javascript" src="https://static.c9.io/nc-3.1.3412-3ebb4f73/static/oldclient/homepage/js/jquery.validate.min.js"></script>
        <script type="text/javascript" src="https://static.c9.io/nc-3.1.3412-3ebb4f73/static/oldclient/homepage/js/components.js"></script>
        <script type="text/javascript" src="https://static.c9.io/nc-3.1.3412-3ebb4f73/static/oldclient/homepage/js/code.js"></script>
        <script type="text/javascript" src="https://static.c9.io/nc-3.1.3412-3ebb4f73/static/oldclient/homepage/js/signin.js"></script>
        <!-- ClickTale Bottom part -->
        <div id="ClickTaleDiv" style="display: none;"></div>
        <script type='text/javascript'>
            document.write(unescape("%3Cscript%20src=\"" + (document.location.protocol == "https:" 
                ? "https://clicktale.pantherssl.com/" 
                : "http://s.clicktale.net/") + "WRc5.js\"%20type=\"text/javascript\"%3E%3C/script%3E"));
            </script>
        <script type="text/javascript">
            var ClickTaleSSL = 1;
            if (typeof ClickTale == "function")
                ClickTale(48230, 1, "www");
        </script>
        <!-- ClickTale end of Bottom part -->
    </body>
</html>
