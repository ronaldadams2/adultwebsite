!DOCTYPE html>
<html lang="en">
<head>
<!-- Matomo -->
<script>
  var _paq = window._paq = window._paq || [];
  /* tracker methods like "setCustomDimension" should be called before "trackPageView" */
  _paq.push(['trackPageView']);
  _paq.push(['enableLinkTracking']);
  (function() {
    var u="https://hairypussy.matomo.cloud/";
    _paq.push(['setTrackerUrl', u+'matomo.php']);
    _paq.push(['setSiteId', '1']);
    var d=document, g=d.createElement('script'), s=d.getElementsByTagName('script')[0];
    g.async=true; g.src='https://cdn.matomo.cloud/hairypussy.matomo.cloud/matomo.js'; s.parentNode.insertBefore(g,s);
  })();
</script>
<!-- End Matomo Code -->

    

    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adult Affiliate Site</title>
    <style>
        body { font-family: Arial, sans-serif; background-color: #111; color: white; text-align: center; }
        .container { max-width: 800px; margin: auto; padding: 20px; }
        .offer { margin: 20px 0; padding: 15px; background: #222; border-radius: 10px; }
        .offer img { max-width: 100%; border-radius: 10px; }
        .offer a { display: block; margin-top: 10px; padding: 10px; background: red; color: white; text-decoration: none; border-radius: 5px; }
        .signup { max-width: 400px; margin: auto; padding: 20px; background: #222; border-radius: 10px; }
        input, button { width: 100%; padding: 10px; margin: 10px 0; border: none; border-radius: 5px; }
        input { background: #333; color: white; }
        button { background: red; color: white; cursor: pointer; }
        .age-verification { position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0, 0, 0, 0.9); display: flex; justify-content: center; align-items: center; }
        .age-verification-box { background: #222; padding: 20px; border-radius: 10px; text-align: center; }
        .age-verification-box button { margin: 10px; }
    </style>
    <script>
        // Age Verification
        function verifyAge() {
            const isAdult = confirm("Are you 18 years or older?");
            if (isAdult) {
                document.querySelector('.age-verification').style.display = 'none';
            } else {
                window.location.href = "https://www.google.com"; // Redirect if underage
            }
        }

        // Form Redirection
        function redirectToLanding(event) {
            event.preventDefault(); // Prevent default form submission
            window.location.href = "landing-page.html"; // Redirect to landing page
        }
    </script>
    <!-- Google Analytics -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=YOUR_GA_TRACKING_ID"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());
        gtag('config', 'YOUR_GA_TRACKING_ID');
    </script>
</head>
<body>
    <!-- Age Verification Popup -->
    <div class="age-verification">
        <div class="age-verification-box">
            <h2>Age Verification</h2>
            <p>You must be 18 years or older to access this site.</p>
            <button onclick="verifyAge()">I am 18 or older</button>
            <button onclick="window.location.href='https://www.google.com'">I am under 18</button>
        </div>
    </div>

    <!-- Main Content -->
    <div class="container">
        <h1>Exclusive Adult Content</h1>
        <p>Check out these hot offers!</p>
        
        <div class="offer">
            <img src="https://www.imglnkx.com/8780/010837A_JRKM_18_ALL_EN_71_L.jpg" alt="Exclusive Offer 1 - Join Now">
            <a href="https://t.mbslr2.com/323467/8780/0?bo=2779,2778,2777,2776,2775&po=6533&aff_sub5=SF_006OG000004lmDN" target="_blank">Access Now</a>
        </div>
        
        <div class="offer">
            <img src="https://www.imglnkx.com/3785/010765A_GDAT_18_ALL_EN_71_L.jpg" alt="Exclusive Offer 2 - Limited Time">
            <a href="https://t.slext2.com/323467/3785/0?bo=2753,2754,2755,2756&po=6456&aff_sub5=SF_006OG000004lmDN" target="_blank">Access Now</a>
        </div>
    </div>
    
    <!-- Signup Form -->
    <h2>Join for Free</h2>
    <div class="signup">
        <form onsubmit="redirectToLanding(event)">
            <input type="text" name="username" placeholder="Enter Username" required>
            <input type="email" name="email" placeholder="Enter Email" required>
            <input type="password" name="password" placeholder="Enter Password" required>
            <button type="submit">Sign Up</button>
        </form>
    </div>

    <!-- Footer with Links -->
    <footer style="margin-top: 20px; font-size: 12px; color: #888;">
        <p>This site is intended for adults only. By accessing this site, you confirm that you are of legal age in your jurisdiction.</p>
        <p>
            <a href="privacy-policy.html" style="color: #888;">Privacy Policy</a> | 
            <a href="terms-of-service.html" style="color: #888;">Terms of Service</a>
        </p>
    </footer>
</body>
</html>
