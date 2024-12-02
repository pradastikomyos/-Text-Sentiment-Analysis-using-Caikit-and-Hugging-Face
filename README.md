<h1 align="center">Proyek Analisis Sentimen dengan gRPC dan HuggingFace Transformers 🌟🧠</h1>
<p align="center">Skrip Python sederhana untuk melakukan analisis sentimen menggunakan layanan gRPC dan model dari HuggingFace Transformers.</p>

<div align="center">
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python Badge">
    <img src="https://img.shields.io/badge/grpc-6554C0?style=for-the-badge&logo=grpc&logoColor=white" alt="gRPC Badge">
    <img src="https://img.shields.io/badge/HuggingFace-yellow?style=for-the-badge&logo=HuggingFace&logoColor=black" alt="HuggingFace Badge">
</div>

---

<h2 align="center">Cara Instalasi dan Penggunaan</h2>

<h3>Langkah Instalasi 🚀</h3>
<ol>
    <li>Klon repositori ini:
        <div style="display: flex; align-items: center; gap: 8px;">
            <textarea id="clone-command" readonly style="width: 80%; resize: none;">git clone https://github.com/username/proyek-analisis-sentimen.git</textarea>
            <button onclick="copyText('clone-command')">Copy</button>
        </div>
    </li>
    <li>Masuk ke folder proyek:
        <div style="display: flex; align-items: center; gap: 8px;">
            <textarea id="cd-command" readonly style="width: 80%; resize: none;">cd proyek-analisis-sentimen</textarea>
            <button onclick="copyText('cd-command')">Copy</button>
        </div>
    </li>
    <li>Instal dependensi:
        <div style="display: flex; align-items: center; gap: 8px;">
            <textarea id="install-command" readonly style="width: 80%; resize: none;">pip install -r requirements.txt</textarea>
            <button onclick="copyText('install-command')">Copy</button>
        </div>
    </li>
</ol>

<h3>Menjalankan Proyek 📄</h3>
<p>Gunakan perintah berikut untuk menjalankan analisis sentimen:</p>
<div style="display: flex; align-items: center; gap: 8px;">
    <textarea id="run-command" readonly style="width: 80%; resize: none;">python main.py</textarea>
    <button onclick="copyText('run-command')">Copy</button>
</div>

<script>
function copyText(elementId) {
    const textarea = document.getElementById(elementId);
    textarea.select();
    document.execCommand('copy');
    alert('Text berhasil disalin ke clipboard!');
}
</script>
