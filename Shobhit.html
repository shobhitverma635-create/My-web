<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EduHub - Educational Platform</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .course-card { transition: all 0.3s ease; position: relative; overflow: hidden; }
        .course-card:hover { transform: translateY(-8px) scale(1.02); box-shadow: 0 20px 40px rgba(0,0,0,0.15); }
        .course-card::before { content: ''; position: absolute; top: 0; left: -100%; width: 100%; height: 100%; background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent); transition: left 0.5s; }
        .course-card:hover::before { left: 100%; }
        .content-item { transition: all 0.2s ease; }
        .content-item:hover { background-color: #f8fafc; transform: translateX(4px); }
        .pdf-viewer { border: 2px solid #e2e8f0; border-radius: 8px; }
        .floating-animation { animation: smoothFloat 4s ease-in-out infinite; }
        @keyframes smoothFloat { 0%, 100% { transform: translateY(0px) rotate(0deg); } 25% { transform: translateY(-8px) rotate(1deg); } 50% { transform: translateY(-12px) rotate(0deg); } 75% { transform: translateY(-8px) rotate(-1deg); } }
        .pulse-animation { animation: smoothPulse 3s ease-in-out infinite; }
        @keyframes smoothPulse { 0%, 100% { opacity: 1; transform: scale(1); } 50% { opacity: 0.8; transform: scale(1.05); } }
        .slide-in { animation: smoothSlideIn 0.8s cubic-bezier(0.25, 0.46, 0.45, 0.94); }
        @keyframes smoothSlideIn { from { opacity: 0; transform: translateY(30px) scale(0.95); } to { opacity: 1; transform: translateY(0) scale(1); } }
        .bounce-in { animation: smoothBounceIn 1s cubic-bezier(0.68, -0.55, 0.265, 1.55); }
        @keyframes smoothBounceIn { 0% { opacity: 0; transform: scale(0.3) rotate(-10deg); } 50% { opacity: 1; transform: scale(1.1) rotate(5deg); } 70% { transform: scale(0.95) rotate(-2deg); } 100% { opacity: 1; transform: scale(1) rotate(0deg); } }
        .gradient-text { background: linear-gradient(45deg, #667eea 0%, #764ba2 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; }
        .ai-moveable { animation: aiFloat 6s ease-in-out infinite; }
        @keyframes aiFloat { 0%, 100% { transform: translateY(0px) translateX(0px) rotate(0deg); } 25% { transform: translateY(-10px) translateX(5px) rotate(2deg); } 50% { transform: translateY(-5px) translateX(-3px) rotate(-1deg); } 75% { transform: translateY(-12px) translateX(2px) rotate(1deg); } }
        .downloads-animation { animation: downloadPulse 2s ease-in-out infinite; }
        @keyframes downloadPulse { 0%, 100% { transform: scale(1); opacity: 0.7; } 50% { transform: scale(1.1); opacity: 1; } }
        .dark-theme { background: #1a1a1a; color: #ffffff; }
        .dark-theme .bg-white { background: #2d2d2d !important; color: #ffffff !important; }
        .video-player-controls { background: linear-gradient(to top, rgba(0,0,0,0.8), transparent); }
    </style>
</head>
<body class="bg-gray-25 min-h-screen" style="background-color: #fefefe;">
    <!-- Header -->
    <header class="bg-white shadow-lg border-b-2 border-orange-500">
        <div class="max-w-7xl mx-auto px-6 py-3">
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-3">
                    <div class="w-12 h-12 bg-orange-500 rounded-full flex items-center justify-center border-2 border-orange-600">
                        <span class="text-white font-bold text-lg">EH</span>
                    </div>
                    <h1 class="text-2xl font-bold text-gray-800">EduHub</h1>
                </div>
                <div class="flex items-center space-x-4">
                    <div id="userStatus" class="text-sm text-gray-600"></div>
                    <div id="ownerControls" class="hidden space-x-2">
                        <button onclick="addNewCourse()" class="bg-orange-500 hover:bg-orange-600 text-white px-6 py-2 rounded-lg font-semibold transition-colors flex items-center space-x-2">
                            <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24"><path d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6v2z"/></svg>
                            <span>Add Course</span>
                        </button>
                        <button onclick="logout()" class="bg-red-500 hover:bg-red-600 text-white px-4 py-2 rounded-lg font-semibold flex items-center space-x-2">
                            <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24"><path d="M17 7l-1.41 1.41L18.17 11H8v2h10.17l-2.58 2.59L17 17l5-5zM4 5h8V3H4c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h8v-2H4V5z"/></svg>
                            <span>Logout</span>
                        </button>
                    </div>
                    <div class="relative">
                        <button onclick="showProfileModal()" class="w-10 h-10 bg-gradient-to-br from-purple-500 to-pink-500 rounded-full flex items-center justify-center text-white font-bold hover:shadow-lg transition-all transform hover:scale-105">
                            <span id="profileInitials">JD</span>
                        </button>
                        <button onclick="toggleProfileMenu()" class="ml-2 p-2 text-gray-600 hover:text-gray-800 hover:bg-gray-100 rounded-lg transition-all">
                            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M12,16A2,2 0 0,1 14,18A2,2 0 0,1 12,20A2,2 0 0,1 10,18A2,2 0 0,1 12,16M12,10A2,2 0 0,1 14,12A2,2 0 0,1 12,14A2,2 0 0,1 10,12A2,2 0 0,1 12,10M12,4A2,2 0 0,1 14,6A2,2 0 0,1 12,8A2,2 0 0,1 10,6A2,2 0 0,1 12,4Z"/></svg>
                        </button>
                        <!-- Profile Menu Dropdown -->
                        <div id="profileMenu" class="hidden absolute right-0 top-12 w-64 bg-white rounded-xl shadow-2xl border border-gray-100 z-50 overflow-hidden">
                            <div class="p-4 bg-gradient-to-r from-purple-500 to-pink-500 text-white">
                                <div class="flex items-center space-x-3">
                                    <div class="w-12 h-12 bg-white bg-opacity-20 rounded-full flex items-center justify-center">
                                        <span class="font-bold">JD</span>
                                    </div>
                                    <div>
                                        <h4 class="font-semibold">John Doe</h4>
                                        <p class="text-sm opacity-90">Class 12 • Science</p>
                                    </div>
                                </div>
                            </div>
                            <div class="p-2">
                                <button onclick="editProfile()" class="w-full text-left px-4 py-3 hover:bg-gray-50 rounded-lg transition-colors flex items-center space-x-3">
                                    <svg class="w-5 h-5 text-gray-500" fill="currentColor" viewBox="0 0 24 24"><path d="M12,2A10,10 0 0,0 2,12A10,10 0 0,0 12,22A10,10 0 0,0 22,12A10,10 0 0,0 12,2M12,8.39C13.57,9.4 15.42,10 17.42,10C18.2,10 18.95,9.91 19.67,9.74C19.88,10.45 20,11.21 20,12C20,16.41 16.41,20 12,20C7.59,20 4,16.41 4,12C4,7.59 7.59,4 12,4C12.79,4 13.55,4.12 14.26,4.33C14.09,5.05 14,5.8 14,6.58C14,7.4 14.09,8.15 14.26,8.87C13.55,8.88 12.79,9 12,9C10.8,9 9.65,8.79 8.61,8.39C9.4,8.15 10.15,8.09 10.87,8.26C11.21,8 11.55,7.88 12,8.39Z"/></svg>
                                    <span>Edit Profile</span>
                                </button>
                                <button onclick="toggleDarkTheme()" class="w-full text-left px-4 py-3 hover:bg-gray-50 rounded-lg transition-colors flex items-center justify-between">
                                    <div class="flex items-center space-x-3">
                                        <svg class="w-5 h-5 text-gray-500" fill="currentColor" viewBox="0 0 24 24"><path d="M17.75,4.09L15.22,6.03L16.13,9.09L13.5,7.28L10.87,9.09L11.78,6.03L9.25,4.09L12.44,4L13.5,1L14.56,4L17.75,4.09M21.25,11L19.61,12.25L20.2,14.23L18.5,13.06L16.8,14.23L17.39,12.25L15.75,11L17.81,10.95L18.5,9L19.19,10.95L21.25,11M18.97,15.95C19.8,15.87 20.69,17.05 20.16,17.8C19.84,18.25 19.5,18.67 19.08,19.07C15.17,23 8.84,23 4.94,19.07C1.03,15.17 1.03,8.83 4.94,4.93C5.34,4.53 5.76,4.17 6.21,3.85C6.96,3.32 8.14,4.21 8.06,5.04C7.79,7.9 8.75,10.87 10.95,13.06C13.14,15.26 16.1,16.22 18.97,15.95M17.33,17.97C14.5,17.81 11.7,16.64 9.53,14.5C7.36,12.31 6.2,9.5 6.04,6.68C3.23,9.82 3.34,14.4 6.35,17.41C9.37,20.43 14,20.54 17.33,17.97Z"/></svg>
                                        <span>Dark Theme</span>
                                    </div>
                                    <button class="relative inline-flex h-5 w-9 items-center rounded-full bg-gray-200 transition-colors focus:outline-none" id="darkThemeToggleMenu">
                                        <span class="inline-block h-3 w-3 transform rounded-full bg-white transition-transform translate-x-1" id="darkThemeSliderMenu"></span>
                                    </button>
                                </button>
                                <button onclick="showNotifications()" class="w-full text-left px-4 py-3 hover:bg-gray-50 rounded-lg transition-colors flex items-center space-x-3">
                                    <svg class="w-5 h-5 text-gray-500" fill="currentColor" viewBox="0 0 24 24"><path d="M21,19V20H3V19L5,17V11C5,7.9 7.03,5.17 10,4.29C10,4.19 10,4.1 10,4A2,2 0 0,1 12,2A2,2 0 0,1 14,4C14,4.1 14,4.19 14,4.29C16.97,5.17 19,7.9 19,11V17L21,19M14,21A2,2 0 0,1 12,23A2,2 0 0,1 10,21"/></svg>
                                    <span>Notifications</span>
                                </button>
                                <button onclick="showSettings()" class="w-full text-left px-4 py-3 hover:bg-gray-50 rounded-lg transition-colors flex items-center space-x-3">
                                    <svg class="w-5 h-5 text-gray-500" fill="currentColor" viewBox="0 0 24 24"><path d="M12,15.5A3.5,3.5 0 0,1 8.5,12A3.5,3.5 0 0,1 12,8.5A3.5,3.5 0 0,1 15.5,12A3.5,3.5 0 0,1 12,15.5M19.43,12.97C19.47,12.65 19.5,12.33 19.5,12C19.5,11.67 19.47,11.34 19.43,11L21.54,9.37C21.73,9.22 21.78,8.95 21.66,8.73L19.66,5.27C19.54,5.05 19.27,4.96 19.05,5.05L16.56,6.05C16.04,5.66 15.5,5.32 14.87,5.07L14.5,2.42C14.46,2.18 14.25,2 14,2H10C9.75,2 9.54,2.18 9.5,2.42L9.13,5.07C8.5,5.32 7.96,5.66 7.44,6.05L4.95,5.05C4.73,4.96 4.46,5.05 4.34,5.27L2.34,8.73C2.22,8.95 2.27,9.22 2.46,9.37L4.57,11C4.53,11.34 4.5,11.67 4.5,12C4.5,12.33 4.53,12.65 4.57,12.97L2.46,14.63C2.27,14.78 2.22,15.05 2.34,15.27L4.34,18.73C4.46,18.95 4.73,19.03 4.95,18.95L7.44,17.94C7.96,18.34 8.5,18.68 9.13,18.93L9.5,21.58C9.54,21.82 9.75,22 10,22H14C14.25,22 14.46,21.82 14.5,21.58L14.87,18.93C15.5,18.68 16.04,18.34 16.56,17.94L19.05,18.95C19.27,19.03 19.54,18.95 19.66,18.73L21.66,15.27C21.78,15.05 21.73,
