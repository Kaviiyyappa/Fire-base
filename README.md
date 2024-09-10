<script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/10.13.1/firebase-app.js";
  import { getAnalytics } from "https://www.gstatic.com/firebasejs/10.13.1/firebase-analytics.js";
  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  const firebaseConfig = {
    apiKey: "AIzaSyAlyXTccFB6EdN5Ok6CInHm3yOFD46e7FA",
    authDomain: "ikbryt-2d555.firebaseapp.com",
    projectId: "ikbryt-2d555",
    storageBucket: "ikbryt-2d555.appspot.com",
    messagingSenderId: "1027628534605",
    appId: "1:1027628534605:web:fa6cb5aa77f7e78464c504",
    measurementId: "G-M1YD05GZTS"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
  const analytics = getAnalytics(app);
</script>
