<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Google Login</title>
    <!-- Load Firebase libraries (adjust version as needed) -->
    <script src="https://www.gstatic.com/firebasejs/9.23.0/firebase-app-compat.js"></script>
    <script src="https://www.gstatic.com/firebasejs/9.23.0/firebase-auth-compat.js"></script>
    <script>
      // Your Firebase configuration – replace with your actual config values.
      const firebaseConfig = {
        apiKey: "AIzaSyDvQvYVbzsfKk_-TTlIruZt7Tf28b_XG_4",
        authDomain: "deskersizer.firebaseapp.com",
        projectId: "deskersizer",
        storageBucket: "deskersizer.firebasestorage.app",
        messagingSenderId: "848878159272",
        appId: "1:848878159272:web:8626b5d20738370924c99d"
      };

      // Initialize Firebase
      firebase.initializeApp(firebaseConfig);

      // Create the Google provider.
      const provider = new firebase.auth.GoogleAuthProvider();

      // Function to trigger sign in on load.
      function signInWithGoogle() {
        // Automatically start the sign-in redirect
        firebase.auth().signInWithRedirect(provider);
      }

      // After the redirect from Google login, handle the result.
      firebase
        .auth()
        .getRedirectResult()
        .then((result) => {
          if (result.user) {
            // Optionally, retrieve the ID token (or any other token you might need)
            result.user.getIdToken().then((token) => {
              // Redirect back to your Electron app using a custom URL scheme.
              // For example, if your app is registered to handle "myapp://" URLs,
              // then navigate to "myapp://login?token=XYZ"
              window.location.href = `myapp://login?token=${token}`;
            });
          }
        })
        .catch((error) => {
          console.error("Error during sign in redirect", error);
          // Optionally, you might display an error message or retry.
        });

      // Automatically trigger sign-in as soon as the page loads.
      window.onload = () => {
        // If there is not already a redirect result, call signInWithGoogle.
        // (This might be refined to check for any previous state.)
        signInWithGoogle();
      };
    </script>
  </head>
  <body>
    <h1>Signing in with Google…</h1>
    <p>If you are not redirected automatically, please check your browser settings.</p>
  </body>
</html>
