<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login - AI Rendering Platform</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <!-- Firebase SDK -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/firebase/10.8.0/firebase-app-compat.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/firebase/10.8.0/firebase-auth-compat.min.js"></script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
        }

        body {
            background: #080810;
            color: #fff;
            line-height: 1.6;
        }

        nav {
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            background: rgba(8, 8, 16, 0.8);
            backdrop-filter: blur(10px);
        }

        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 1.5rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            background: linear-gradient(45deg, #00f2fe, #4facfe);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .nav-links {
            display: flex;
            gap: 2rem;
        }

        .nav-links a {
            color: #fff;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        .nav-links a:hover {
            color: #4facfe;
        }

        main {
            padding-top: 120px;
            padding-bottom: 4rem;
            max-width: 1200px;
            margin: 0 auto;
            padding-left: 2rem;
            padding-right: 2rem;
            min-height: calc(100vh - 80px);
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .login-container {
            background: rgba(255, 255, 255, 0.05);
            padding: 3rem;
            border-radius: 20px;
            backdrop-filter: blur(10px);
            width: 100%;
            max-width: 500px;
        }

        .section-title {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            background: linear-gradient(45deg, #00f2fe, #4facfe);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-align: center;
        }

        .section-subtitle {
            color: #a0a0a0;
            text-align: center;
            margin-bottom: 2rem;
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            color: #fff;
            font-weight: 500;
        }

        .form-group input {
            width: 100%;
            padding: 1rem;
            background: rgba(255, 255, 255, 0.1);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 10px;
            color: #fff;
            font-size: 1rem;
            transition: border-color 0.3s ease;
        }

        .form-group input:focus {
            outline: none;
            border-color: #4facfe;
        }

        .forgot-password {
            text-align: right;
            margin-top: -1rem;
            margin-bottom: 1.5rem;
        }

        .forgot-password a {
            color: #4facfe;
            text-decoration: none;
            font-size: 0.9rem;
        }

        .forgot-password a:hover {
            text-decoration: underline;
        }

        .submit-button {
            width: 100%;
            padding: 1rem 2rem;
            background: linear-gradient(45deg, #00f2fe, #4facfe);
            color: #fff;
            border: none;
            border-radius: 30px;
            font-weight: 600;
            font-size: 1rem;
            cursor: pointer;
            transition: transform 0.3s ease;
        }

        .submit-button:hover {
            transform: translateY(-2px);
        }

        .signup-link {
            text-align: center;
            margin-top: 1.5rem;
            color: #a0a0a0;
        }

        .signup-link a {
            color: #4facfe;
            text-decoration: none;
            font-weight: 500;
        }

        .signup-link a:hover {
            text-decoration: underline;
        }

        .social-login {
            margin-top: 2rem;
            text-align: center;
        }

        .social-login p {
            color: #a0a0a0;
            margin-bottom: 1rem;
        }

        .social-buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
        }

        .social-button {
            padding: 0.8rem 1.5rem;
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 30px;
            background: rgba(255, 255, 255, 0.05);
            color: #fff;
            text-decoration: none;
            transition: background-color 0.3s ease;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            cursor: pointer;
        }

        .social-button:hover {
            background: rgba(255, 255, 255, 0.1);
        }

        .error-message {
            color: #ff4d4d;
            text-align: center;
            margin-top: 1rem;
            display: none;
        }

        footer {
            text-align: center;
            padding: 2rem;
            color: #a0a0a0;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }

        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }

            .login-container {
                padding: 2rem;
            }

            .section-title {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <nav>
        <div class="nav-container">
            <img src="//b9fe070413d9eb020045866da2feb86e.cdn.bubble.io/f1728834965913x568986154418384060/2.svg" 
                 width="200" 
                 height="100" 
                 alt="Logo"
                 class="absolute right-4 top-2">
            <div class="nav-links">
                <a href="#features">Features</a>
                <a href="#pricing">Pricing</a>
                <a href="#support">Support</a>
            </div>
        </div>
    </nav>

    <main>
        <div class="login-container">
            <h1 class="section-title">Welcome Back</h1>
            <p class="section-subtitle">Log in to your account</p>

            <form id="login-form" onsubmit="handleLogin(event)">
                <div class="form-group">
                    <label for="email">Email Address</label>
                    <input type="email" id="email" name="email" required>
                </div>

                <div class="form-group">
                    <label for="password">Password</label>
                    <input type="password" id="password" name="password" required>
                </div>

                <div class="forgot-password">
                    <a href="/forgot-password">Forgot password?</a>
                </div>

                <div id="error-message" class="error-message"></div>

                <button type="submit" class="submit-button">Log In</button>
            </form>

            <div class="signup-link">
                Don't have an account? <a href="/signup">Sign up</a>
            </div>

            <div class="social-login">
                <p>Or log in with</p>
                <div class="social-buttons">
                    <button onclick="signInWithGoogle()" class="social-button">
                        <img src="/api/placeholder/20/20" alt="Google">
                        Google
                    </button>
                    <button onclick="signInWithGitHub()" class="social-button">
                        <img src="/api/placeholder/20/20" alt="GitHub">
                        GitHub
                    </button>
                </div>
            </div>
        </div>
    </main>

    <footer>
        <p>&copy; 2024 Company. All rights reserved.</p>
    </footer>

    <script>
        // Firebase configuration - Replace with your Firebase config
        const firebaseConfig = {
            apiKey: "YOUR_API_KEY",
            authDomain: "your-app.firebaseapp.com",
            projectId: "your-project-id",
            storageBucket: "your-app.appspot.com",
            messagingSenderId: "your-messaging-sender-id",
            appId: "your-app-id"
        };

        // Initialize Firebase
        firebase.initializeApp(firebaseConfig);
        const auth = firebase.auth();

        // Show error message
        function showError(message) {
            const errorElement = document.getElementById('error-message');
            errorElement.textContent = message;
            errorElement.style.display = 'block';
        }

        // Handle login form submission
        async function handleLogin(event) {
            event.preventDefault();
            
            const email = document.getElementById('email').value;
            const password = document.getElementById('password').value;

            try {
                await auth.signInWithEmailAndPassword(email, password);
                // Redirect to dashboard on successful login
                window.location.href = '/dashboard';
            } catch (error) {
                showError(error.message);
            }
        }

        // Google Sign In
        async function signInWithGoogle() {
            const provider = new firebase.auth.GoogleAuthProvider();
            try {
                await auth.signInWithPopup(provider);
                window.location.href = '/dashboard';
            } catch (error) {
                showError(error.message);
            }
        }

        // GitHub Sign In
        async function signInWithGitHub() {
            const provider = new firebase.auth.GithubAuthProvider();
            try {
                await auth.signInWithPopup(provider);
                window.location.href = '/dashboard';
            } catch (error) {
                showError(error.message);
            }
        }

        // Listen for auth state changes
        auth.onAuthStateChanged((user) => {
            if (user) {
                // User is signed in, redirect to dashboard
                window.location.href = '/dashboard';
            }
        });
    </script>
</body>
</html>
