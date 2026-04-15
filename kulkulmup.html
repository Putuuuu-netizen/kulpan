// Inisialisasi Animasi Scroll (AOS)
AOS.init({
    duration: 1000, // Durasi animasi 1 detik
    once: true,     // Animasi cuma sekali pas scroll ke bawah
});

// --- KONFIGURASI ---
const correctPass = "112325"; // Tanggal jadian (Password)

// Fungsi Cek Password
function checkPassword() {
    const input = document.getElementById("pass-input").value;
    const overlay = document.getElementById("login-overlay");
    const bgMusic = document.getElementById("bg-music");
    const errorMsg = document.getElementById("error-msg");

    if (input === correctPass) {
        // 1. Efek Confetti (Meledak)
        confetti({
            particleCount: 200,
            spread: 100,
            origin: { y: 0.6 },
            colors: ['#8d6e63', '#d7ccc8', '#ffccd5']
        });
        
        // 2. Hilangkan Layar Login pelan-pelan
        overlay.style.transition = "opacity 0.8s ease";
        overlay.style.opacity = 0;
        
        setTimeout(() => {
            overlay.style.display = "none";
            
            // 3. Mulai Musik & Teks
            bgMusic.play().catch(error => console.log("User must interact first"));
            startTypewriter();
            
            // Ubah icon musik jadi pause
            document.getElementById("music-icon").classList.add("fa-spin");
        }, 800);
    } else {
        // Kalau salah
        errorMsg.style.display = "block";
        // Animasi getar dikit
        document.querySelector('.input-line').style.borderColor = "red";
        setTimeout(() => {
            document.querySelector('.input-line').style.borderColor = "#8d6e63";
        }, 500);
    }
}

function startTypewriter() {
    // BARIS PENTING: Kosongkan dulu teksnya biar gak dobel
    document.getElementById("typewriter-text").innerHTML = "";

    new TypeIt("#typewriter-text", {
        speed: 50, // Kecepatan ngetik (makin kecil makin ngebut)
        waitUntilVisible: true,
        cursor: true,
    })
    .type("Untuk kulkul, perempuanku.")
    .pause(1000).break()
    .type("Selamat datang di usia 17tahun.")
    .pause(500).break()
    .type("Dunia mungkin akan semakin berisik,")
    .pause(500)
    .type(" tapi tenang saja...")
    .pause(500).break()
    .type("Ada aku di sini yang siap mendengarkan.")
    .go();
}
// Fungsi Tombol Musik
let isPlaying = true;
function toggleMusic() {
    const music = document.getElementById("bg-music");
    const icon = document.getElementById("music-icon");
    
    if (music.paused) {
        music.play();
        icon.classList.remove("fa-play");
        icon.classList.add("fa-music");
        icon.classList.add("fa-spin");
    } else {
        music.pause();
        icon.classList.remove("fa-music");
        icon.classList.remove("fa-spin");
        icon.classList.add("fa-play");
    }
}

// Biar bisa tekan Enter pas login
document.getElementById("pass-input").addEventListener("keypress", function(e) {
    if (e.key === "Enter") checkPassword();
});
