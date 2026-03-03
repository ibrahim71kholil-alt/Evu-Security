<script type="module">
  import { initializeApp } from "https://www.gstatic.com/firebasejs/10.12.2/firebase-app.js";
  import { getAuth } from "https://www.gstatic.com/firebasejs/10.12.2/firebase-auth.js";
  import { getAnalytics } from "https://www.gstatic.com/firebasejs/10.12.2/firebase-analytics.js";

  const firebaseConfig = {
    apiKey: "AIzaSyCGEgnFT8a-Dbik2W6JqpP88-PwlWfnecE",
    authDomain: "evu-8921a.firebaseapp.com",
    projectId: "evu-8921a",
    storageBucket: "evu-8921a.appspot.com",
    messagingSenderId: "777966469701",
    appId: "1:777966469701:web:e782d1df25f7246adf592c",
    measurementId: "G-3BFDY5B1CM"
  };

  const app = initializeApp(firebaseConfig);
  const auth = getAuth(app);
  const analytics = getAnalytics(app);
</script>
