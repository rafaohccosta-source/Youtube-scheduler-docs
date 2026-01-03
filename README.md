1|<!DOCTYPE html>
2|<html lang="pt-BR">
3|<head>
4|    <meta charset="UTF-8">
5|    <meta name="viewport" content="width=device-width, initial-scale=1.0">
6|    <title>YouTube Scheduler - App de Agendamento</title>
7|    <style>
8|        * {
9|            margin: 0;
10|            padding: 0;
11|            box-sizing: border-box;
12|        }
13|        
14|        body {
15|            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Arial, sans-serif;
16|            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
17|            min-height: 100vh;
18|            display: flex;
19|            align-items: center;
20|            justify-content: center;
21|            color: white;
22|        }
23|        
24|        .container {
25|            text-align: center;
26|            padding: 40px;
27|            max-width: 600px;
28|        }
29|        
30|        .logo {
31|            font-size: 80px;
32|            margin-bottom: 20px;
33|            animation: pulse 2s infinite;
34|        }
35|        
36|        @keyframes pulse {
37|            0%, 100% { transform: scale(1); }
38|            50% { transform: scale(1.1); }
39|        }
40|        
41|        h1 {
42|            font-size: 3em;
43|            margin-bottom: 20px;
44|            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
45|        }
46|        
47|        p {
48|            font-size: 1.2em;
49|            margin-bottom: 30px;
50|            opacity: 0.9;
51|        }
52|        
53|        .button {
54|            display: inline-block;
55|            background-color: #FF0000;
56|            color: white;
57|            padding: 15px 40px;
58|            text-decoration: none;
59|            border-radius: 50px;
60|            font-size: 1.2em;
61|            font-weight: bold;
62|            transition: transform 0.3s, box-shadow 0.3s;
63|            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
64|        }
65|        
66|        .button:hover {
67|            transform: translateY(-2px);
68|            box-shadow: 0 6px 20px rgba(0,0,0,0.3);
69|        }
70|        
71|        .links {
72|            margin-top: 40px;
73|            padding-top: 40px;
74|            border-top: 1px solid rgba(255,255,255,0.3);
75|        }
76|        
77|        .links a {
78|            color: white;
79|            text-decoration: none;
80|            margin: 0 15px;
81|            opacity: 0.8;
82|            transition: opacity 0.3s;
83|        }
84|        
85|        .links a:hover {
86|            opacity: 1;
87|            text-decoration: underline;
88|        }
89|        
90|        .features {
91|            margin-top: 40px;
92|            display: grid;
93|            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
94|            gap: 20px;
95|            text-align: left;
96|        }
97|        
98|        .feature {
99|            background: rgba(255,255,255,0.1);
100|            padding: 20px;
101|            border-radius: 10px;
102|            backdrop-filter: blur(10px);
103|        }
104|        
105|        .feature-icon {
106|            font-size: 2em;
107|            margin-bottom: 10px;
108|        }
109|    </style>
110|</head>
111|<body>
112|    <div class="container">
113|        <div class="logo">▶️</div>
114|        <h1>YouTube Scheduler</h1>
115|        <p>Agende suas publicações no YouTube com facilidade</p>
116|        
117|        <a href="https://yt-content-planner.preview.emergentagent.com" class="button">
118|            Acessar App
119|        </a>
120|        
121|        <div class="features">
122|            <div class="feature">
123|                <div class="feature-icon">🎬</div>
124|                <strong>Upload Fácil</strong>
125|                <p style="font-size: 0.9em; margin-top: 10px;">Selecione vídeos do seu dispositivo</p>
126|            </div>
127|            <div class="feature">
128|                <div class="feature-icon">⏰</div>
129|                <strong>Agendamento</strong>
130|                <p style="font-size: 0.9em; margin-top: 10px;">Escolha data e hora de publicação</p>
131|            </div>
132|            <div class="feature">
133|                <div class="feature-icon">📝</div>
134|                <strong>Descrições</strong>
135|                <p style="font-size: 0.9em; margin-top: 10px;">Adicione títulos, descrições e hashtags</p>
136|            </div>
137|        </div>
138|        
139|        <div class="links">
140|            <a href="privacy.html">Política de Privacidade</a>
141|            <a href="terms.html">Termos de Serviço</a>
142|        </div>
143|    </div>
144|</body>
145|</html>
146|





        
        .feature {
            background: rgba(255,255,255,0.1);
            padding: 20px;
            border-radius: 10px;
            backdrop-filter: blur(10px);
        }
        
        .feature-icon {
            font-size: 2em;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <div class=\"container\">
        <div class=\"logo\">▶️</div>
        <h1>YouTube Scheduler</h1>
        <p>Agende suas publicações no YouTube com facilidade</p>
        
        <a href=\"https://yt-content-planner.preview.emergentagent.com\" class=\"button\">
            Acessar App
        </a>
        
        <div class=\"features\">
            <div class=\"feature\">
                <div class=\"feature-icon\">🎬</div>
                <strong>Upload Fácil</strong>
                <p style=\"font-size: 0.9em; margin-top: 10px;\">Selecione vídeos do seu dispositivo</p>
            </div>
            <div class=\"feature\">
                <div class=\"feature-icon\">⏰</div>
                <strong>Agendamento</strong>
                <p style=\"font-size: 0.9em; margin-top: 10px;\">Escolha data e hora de publicação</p>
            </div>
            <div class=\"feature\">
                <div class=\"feature-icon\">📝</div>
                <strong>Descrições</strong>
                <p style=\"font-size: 0.9em; margin-top: 10px;\">Adicione títulos, descrições e hashtags</p>
            </div>
        </div>
        
        <div class=\"links\">
            <a href=\"privacy.html\">Política de Privacidade</a>
            <a href=\"terms.html\">Termos de Serviço</a>
        </div>
    </div>
</body>
</html>
"
Observation: Create successful: /app/github_pages/index.html

Fetching debug logs for expo

==> /var/log/supervisor/expo.err.log <==
  expo-image@2.4.0 - expected version: ~3.0.11
  expo-linking@7.1.7 - expected version: ~8.0.11
  expo-router@5.1.4 - expected version: ~6.0.21
  expo-splash-screen@0.30.10 - expected version: ~31.0.13
  expo-status-bar@2.2.3 - expected version: ~3.0.9
  expo-symbols@0.4.5 - expected version: ~1.0.8
  expo-system-ui@5.0.10 - expected version: ~6.0.9
  react@19.0.0 - expected version: 19.1.0
  react-dom@19.0.0 - expected version: 19.1.0
  react-native@0.79.5 - expected version: 0.81.5
  react-native-gesture-handler@2.24.0 - expected version: ~2.28.0
  react-native-reanimated@3.17.5 - expected version: ~4.1.1
  react-native-safe-area-context@5.4.0 - expected version: ~5.6.0
  react-native-screens@4.11.1 - expected version: ~4.16.0
  react-native-web@0.20.0 - expected version: ^0.21.0
  react-native-webview@13.13.5 - expected version: 13.15.0
  @types/react@19.0.14 - expected version: ~19.1.10
  eslint-config-expo@9.2.0 - expected version: ~10.0.0
  typescript@5.8.3 - expected version: ~5.9.2
Your project may not work correctly until you install the expected versions of the packages.

==> /var/log/supervisor/expo.out.log <==
 LOG  [web] Logs will appear in the browser console
 LOG  [web] Logs will appear in the browser console
Web node_modules/expo-router/entry.js ░░░░░░░░░░░░░░░░  0.0% (0/1)
λ Bundled 26ms node_modules/expo-router/node/render.js (1 module)
Web Bundled 347ms node_modules/expo-router/entry.js (1 module)
Web Bundled 36ms node_modules/expo-router/entry.js (1 module)
 LOG  [web] Logs will appear in the browser console
 LOG  [web] Logs will appear in the browser console
yarn run v1.22.22
$ /app/frontend/node_modules/.bin/expo start --tunnel --port 3000
env: load .env
env: export EXPO_TUNNEL_SUBDOMAIN EXPO_PACKAGER_HOSTNAME EXPO_PUBLIC_BACKEND_URL EXPO_USE_FAST_RESOLVER METRO_CACHE_ROOT
Starting project at /app/frontend
Fast resolver is enabled.
Metro is running in CI mode, reloads are disabled. Remove CI=true to enable watch mode.
Starting Metro Bundler
Tunnel connected.
Tunnel ready.
Waiting on http://localhost:3000
Logs for your project will appear below.


Fetching debug logs for backend

==> /var/log/supervisor/backend.err.log <==
INFO:     Shutting down
INFO:     Waiting for application shutdown.
2026-01-02 01:06:18,084 - apscheduler.scheduler - INFO - Scheduler has been shut down
INFO:     Application shutdown complete.
INFO:     Finished server process [244]
INFO:     Started server process [325]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
INFO:     Will watch for changes in these directories: ['/app/backend']
INFO:     Uvicorn running on http://0.0.0.0:8001 (Press CTRL+C to quit)
INFO:     Started reloader process [98] using WatchFiles
INFO:     Started server process [133]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
INFO:     Will watch for changes in these directories: ['/app/backend']
INFO:     Uvicorn running on http://0.0.0.0:8001 (Press CTRL+C to quit)
INFO:     Started reloader process [97] using WatchFiles
INFO:     Started server process [134]
INFO:     Waiting for application startup.
INFO:     Application startup complete.

==> /var/log/supervisor/backend.out.log <==
INFO:     127.0.0.1:49520 - "GET /api/ HTTP/1.1" 200 OK
INFO:     127.0.0.1:49530 - "GET /api/auth/url HTTP/1.1" 200 OK
INFO:     10.64.140.168:46540 - "GET /api/auth/url HTTP/1.1" 200 OK
INFO:     127.0.0.1:41052 - "GET /api/ HTTP/1.1" 200 OK
INFO:     127.0.0.1:50186 - "GET /api/ HTTP/1.1" 200 OK
INFO:     127.0.0.1:50202 - "GET /api/auth/url HTTP/1.1" 200 OK
INFO:     127.0.0.1:50206 - "GET /api/videos/test-user-123 HTTP/1.1" 200 OK
INFO:     10.64.130.161:46150 - "GET /api/auth/url HTTP/1.1" 200 OK
INFO:     10.64.133.143:59164 - "GET /api/auth/url HTTP/1.1" 200 OK
INFO:     127.0.0.1:33982 - "GET /api/privacy-policy HTTP/1.1" 200 OK
INFO:     10.64.128.205:57152 - "GET /api/privacy-policy HTTP/1.1" 200 OK


Fetching debug logs for mongodb

tail: cannot open '/var/log/supervisor/mongodb*.log' for reading: No such file or directory# Youtube-scheduler-docs
