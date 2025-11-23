fileInput.addEventListener('change', async (e) => {
        const file = e.target.files[0];
        if (!file) return;

        statusDiv.innerText = "Processant imatge..."; // Aquesta és la línia que hauria de canviar
        statusDiv.className = "";
        // ...
