# MuradJournal
Murad's Journal
পাসওয়ার্ড পরিবর্তন করতে খুব সহজ। শুধু JavaScript কোডের দুটি জায়গা পরিবর্তন করতে হবে:
// ১. লগিন ফাংশনে (লাইন প্রায় ৯০০-এর কাছাকাছি)
function handleLogin() {
    const username = document.getElementById('username').value;
    const password = document.getElementById('password').value;

    // এই লাইনটি খুঁজুন:
    if (username === 'murad' && password === 'murad2006') {
        // এখানে 'murad2006' পরিবর্তন করে নতুন পাসওয়ার্ড দিন
    }
}

// ২. ভেরিফিকেশন ফাংশনেও (লাইন প্রায় ৯৫০-এর কাছাকাছি)
function verifyAndProceed() {
    const username = document.getElementById('verifyUsername').value;
    const password = document.getElementById('verifyPassword').value;

    // এই লাইনটি খুঁজুন:
    if (username === 'murad' && password === 'murad2006') {
        // এখানেও 'murad2006' পরিবর্তন করুন
    }
}
