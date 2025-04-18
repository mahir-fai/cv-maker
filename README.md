<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Free online tool to compress your CV/resume files while maintaining quality. Optimize PDF, DOCX, and image files for smaller size.">
    <meta name="keywords" content="CV compression, resume optimizer, PDF compressor, DOCX reducer, file size reducer">
    <title>CV Compressor Pro | Optimize Your Resume File Size</title>
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_ADSENSE_ID" crossorigin="anonymous"></script>
    <style>
        :root {
            --primary-color: #4a6bff;
            --secondary-color: #f8f9fa;
            --accent-color: #ff6b6b;
            --text-color: #333;
            --light-text: #6c757d;
            --border-radius: 8px;
            --box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f5f7ff;
            color: var(--text-color);
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header {
            background-color: white;
            box-shadow: var(--box-shadow);
            padding: 20px 0;
            margin-bottom: 30px;
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 24px;
            font-weight: 700;
            color: var(--primary-color);
            text-decoration: none;
        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav ul li {
            margin-left: 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: var(--text-color);
            font-weight: 500;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: var(--primary-color);
        }

        .hero {
            text-align: center;
            margin-bottom: 40px;
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 15px;
            color: var(--primary-color);
        }

        .hero p {
            color: var(--light-text);
            max-width: 700px;
            margin: 0 auto 25px;
        }

        .main-content {
            display: grid;
            grid-template-columns: 1fr 300px;
            gap: 30px;
        }

        @media (max-width: 768px) {
            .main-content {
                grid-template-columns: 1fr;
            }
        }

        .compression-tool {
            background-color: white;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            padding: 30px;
            margin-bottom: 30px;
        }

        .tool-title {
            font-size: 1.5rem;
            margin-bottom: 20px;
            color: var(--primary-color);
        }

        .file-upload {
            border: 2px dashed #ddd;
            border-radius: var(--border-radius);
            padding: 40px;
            text-align: center;
            margin-bottom: 25px;
            cursor: pointer;
            transition: all 0.3s;
        }

        .file-upload:hover {
            border-color: var(--primary-color);
            background-color: rgba(74, 107, 255, 0.05);
        }

        .file-upload i {
            font-size: 48px;
            color: var(--primary-color);
            margin-bottom: 15px;
        }

        .file-upload p {
            margin-bottom: 10px;
        }

        .file-upload input {
            display: none;
        }

        .btn {
            background-color: var(--primary-color);
            color: white;
            border: none;
            padding: 12px 24px;
            border-radius: var(--border-radius);
            cursor: pointer;
            font-weight: 600;
            transition: all 0.3s;
            display: inline-block;
        }

        .btn:hover {
            background-color: #3a5aed;
            transform: translateY(-2px);
        }

        .btn-outline {
            background-color: transparent;
            border: 1px solid var(--primary-color);
            color: var(--primary-color);
        }

        .btn-outline:hover {
            background-color: rgba(74, 107, 255, 0.1);
        }

        .compression-options {
            margin-bottom: 25px;
        }

        .option-title {
            font-weight: 600;
            margin-bottom: 10px;
        }

        .slider-container {
            margin-bottom: 15px;
        }

        .slider {
            width: 100%;
            height: 8px;
            border-radius: 4px;
            background: #ddd;
            outline: none;
            -webkit-appearance: none;
        }

        .slider::-webkit-slider-thumb {
            -webkit-appearance: none;
            appearance: none;
            width: 20px;
            height: 20px;
            border-radius: 50%;
            background: var(--primary-color);
            cursor: pointer;
        }

        .slider-labels {
            display: flex;
            justify-content: space-between;
            margin-top: 5px;
            color: var(--light-text);
            font-size: 0.9rem;
        }

        .checkbox-option {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
        }

        .checkbox-option input {
            margin-right: 10px;
        }

        .results {
            display: none;
            background-color: #f8f9fa;
            border-radius: var(--border-radius);
            padding: 20px;
            margin-top: 20px;
        }

        .result-row {
            display: flex;
            justify-content: space-between;
            margin-bottom: 15px;
            padding-bottom: 15px;
            border-bottom: 1px solid #eee;
        }

        .result-row:last-child {
            border-bottom: none;
            margin-bottom: 0;
            padding-bottom: 0;
        }

        .result-label {
            font-weight: 600;
        }

        .result-value {
            color: var(--primary-color);
            font-weight: 600;
        }

        .sidebar {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        .ad-unit {
            background-color: white;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            padding: 20px;
            text-align: center;
            min-height: 250px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .ad-unit p {
            color: var(--light-text);
        }

        .info-box {
            background-color: white;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            padding: 20px;
        }

        .info-box h3 {
            margin-bottom: 15px;
            color: var(--primary-color);
        }

        .info-box ul {
            list-style-position: inside;
            margin-bottom: 15px;
        }

        .info-box li {
            margin-bottom: 8px;
        }

        footer {
            background-color: white;
            padding: 30px 0;
            margin-top: 50px;
            box-shadow: 0 -4px 12px rgba(0, 0, 0, 0.05);
        }

        .footer-content {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 30px;
        }

        .footer-section {
            flex: 1;
            min-width: 200px;
        }

        .footer-section h3 {
            margin-bottom: 15px;
            color: var(--primary-color);
        }

        .footer-section ul {
            list-style: none;
        }

        .footer-section ul li {
            margin-bottom: 10px;
        }

        .footer-section ul li a {
            text-decoration: none;
            color: var(--light-text);
            transition: color 0.3s;
        }

        .footer-section ul li a:hover {
            color: var(--primary-color);
        }

        .copyright {
            text-align: center;
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid #eee;
            color: var(--light-text);
        }

        /* Responsive adjustments */
        @media (max-width: 600px) {
            .header-content {
                flex-direction: column;
                gap: 15px;
            }
            
            nav ul {
                justify-content: center;
            }
            
            nav ul li {
                margin: 0 10px;
            }
            
            .hero h1 {
                font-size: 1.8rem;
            }
            
            .file-upload {
                padding: 30px 15px;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container header-content">
            <a href="#" class="logo">CV Compressor Pro</a>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">How It Works</a></li>
                    <li><a href="#">Features</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="container">
        <section class="hero">
            <h1>Optimize Your CV File Size</h1>
            <p>Reduce your resume file size without losing quality. Perfect for email attachments and online applications.</p>
        </section>

        <div class="main-content">
            <div class="compression-tool">
                <h2 class="tool-title">Compress Your CV</h2>
                
                <div class="file-upload" id="dropArea">
                    <i>📄</i>
                    <p><strong>Drag & drop your CV file here</strong></p>
                    <p>or</p>
                    <input type="file" id="fileInput" accept=".pdf,.docx,.jpg,.jpeg,.png">
                    <button class="btn">Select File</button>
                    <p class="file-types">Supports: PDF, DOCX, JPG, PNG</p>
                </div>
                
                <div class="compression-options">
                    <h3 class="option-title">Compression Settings</h3>
                    
                    <div class="slider-container">
                        <label for="compressionLevel">Compression Level:</label>
                        <input type="range" id="compressionLevel" class="slider" min="0" max="100" value="50">
                        <div class="slider-labels">
                            <span>Low</span>
                            <span>Medium</span>
                            <span>High</span>
                        </div>
                    </div>
                    
                    <div class="checkbox-option">
                        <input type="checkbox" id="preserveQuality" checked>
                        <label for="preserveQuality">Preserve text quality</label>
                    </div>
                    
                    <div class="checkbox-option">
                        <input type="checkbox" id="removeMetadata">
                        <label for="removeMetadata">Remove metadata</label>
                    </div>
                </div>
                
                <button class="btn" id="compressBtn" disabled>Compress Now</button>
                
                <div class="results" id="resultsSection">
                    <div class="result-row">
                        <span class="result-label">Original Size:</span>
                        <span class="result-value" id="originalSize">-</span>
                    </div>
                    <div class="result-row">
                        <span class="result-label">Compressed Size:</span>
                        <span class="result-value" id="compressedSize">-</span>
                    </div>
                    <div class="result-row">
                        <span class="result-label">Reduction:</span>
                        <span class="result-value" id="reduction">-</span>
                    </div>
                    <div class="result-row">
                        <span class="result-label">Time:</span>
                        <span class="result-value" id="compressionTime">-</span>
                    </div>
                    
                    <button class="btn" id="downloadBtn">Download Compressed File</button>
                    <button class="btn btn-outline" id="newFileBtn">Compress Another File</button>
                </div>
            </div>
            
            <div class="sidebar">
                <div class="ad-unit">
                    <!-- Replace with your AdSense code -->
                    <ins class="adsbygoogle"
                         style="display:block"
                         data-ad-client="ca-app-pub-9529109133395287/2296215605"
                         data-ad-slot="9241193054"
                         data-ad-format="auto"
                         data-full-width-responsive="true"></ins>
                    <script>
                         (adsbygoogle = window.adsbygoogle || []).push({});
                    </script>
                </div>
                
                <div class="info-box">
                    <h3>Why Compress Your CV?</h3>
                    <ul>
                        <li>Smaller files upload faster</li>
                        <li>Meet application size limits</li>
                        <li>Easier email attachments</li>
                        <li>Faster loading on applicant systems</li>
                    </ul>
                    <p>Our tool keeps your formatting intact while reducing file size.</p>
                </div>
                
                <div class="ad-unit">
                    <!-- Second ad unit -->
                    <ins class="adsbygoogle"
                         style="display:block"
                         data-ad-client="ca-app-pub-9529109133395287/2296215605"
                         data-ad-slot="9241193054"
                         data-ad-format="auto"
                         data-full-width-responsive="true"></ins>
                    <script>
                         (adsbygoogle = window.adsbygoogle || []).push({});
                    </script>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <div class="container footer-content">
            <div class="footer-section">
                <h3>CV Compressor Pro</h3>
                <p>The fastest way to optimize your resume for online applications and email attachments.</p>
            </div>
            <div class="footer-section">
                <h3>Quick Links</h3>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Privacy Policy</a></li>
                    <li><a href="#">Terms of Service</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h3>Supported Formats</h3>
                <ul>
                    <li><a href="#">PDF Compression</a></li>
                    <li><a href="#">Word DOCX</a></li>
                    <li><a href="#">JPG/PNG Images</a></li>
                    <li><a href="#">Text Optimization</a></li>
                </ul>
            </div>
        </div>
        <div class="container copyright">
            <p>&copy; 2023 CV Compressor Pro. All rights reserved.</p>
        </div>
    </footer>

    <script>
        // DOM Elements
        const fileInput = document.getElementById('fileInput');
        const dropArea = document.getElementById('dropArea');
        const compressBtn = document.getElementById('compressBtn');
        const downloadBtn = document.getElementById('downloadBtn');
        const newFileBtn = document.getElementById('newFileBtn');
        const resultsSection = document.getElementById('resultsSection');
        
        // File handling
        let selectedFile = null;
        
        // Event listeners for file selection
        dropArea.addEventListener('click', () => fileInput.click());
        
        fileInput.addEventListener('change', (e) => {
            if (e.target.files.length) {
                handleFileSelection(e.target.files[0]);
            }
        });
        
        // Drag and drop functionality
        ['dragenter', 'dragover', 'dragleave', 'drop'].forEach(eventName => {
            dropArea.addEventListener(eventName, preventDefaults, false);
        });
        
        function preventDefaults(e) {
            e.preventDefault();
            e.stopPropagation();
        }
        
        ['dragenter', 'dragover'].forEach(eventName => {
            dropArea.addEventListener(eventName, highlight, false);
        });
        
        ['dragleave', 'drop'].forEach(eventName => {
            dropArea.addEventListener(eventName, unhighlight, false);
        });
        
        function highlight() {
            dropArea.classList.add('highlight');
        }
        
        function unhighlight() {
            dropArea.classList.remove('highlight');
        }
        
        dropArea.addEventListener('drop', (e) => {
            const dt = e.dataTransfer;
            const file = dt.files[0];
            handleFileSelection(file);
        });
        
        function handleFileSelection(file) {
            // Validate file type
            const validTypes = ['application/pdf', 'application/vnd.openxmlformats-officedocument.wordprocessingml.document', 'image/jpeg', 'image/png'];
            
            if (!validTypes.includes(file.type)) {
                alert('Please upload a valid file type (PDF, DOCX, JPG, PNG)');
                return;
            }
            
            selectedFile = file;
            compressBtn.disabled = false;
            
            // Update UI to show selected file
            const fileInfo = document.createElement('div');
            fileInfo.innerHTML = `
                <p><strong>Selected file:</strong> ${file.name}</p>
                <p>Size: ${formatFileSize(file.size)}</p>
            `;
            dropArea.innerHTML = '';
            dropArea.appendChild(fileInfo);
        }
        
        // Compression functionality
        compressBtn.addEventListener('click', () => {
            if (!selectedFile) return;
            
            // Show loading state
            compressBtn.textContent = 'Compressing...';
            compressBtn.disabled = true;
            
            // Simulate compression (in a real app, you would use actual compression libraries)
            setTimeout(() => {
                // Calculate "compressed" size based on compression level
                const compressionLevel = parseInt(document.getElementById('compressionLevel').value);
                const reductionPercentage = 20 + (compressionLevel * 0.6); // 20-80% reduction
                const compressedSize = selectedFile.size * (1 - (reductionPercentage / 100));
                
                // Update results
                document.getElementById('originalSize').textContent = formatFileSize(selectedFile.size);
                document.getElementById('compressedSize').textContent = formatFileSize(compressedSize);
                document.getElementById('reduction').textContent = `${Math.round(reductionPercentage)}%`;
                document.getElementById('compressionTime').textContent = '1.2s';
                
                // Show results
                resultsSection.style.display = 'block';
                compressBtn.textContent = 'Compress Now';
                
                // Scroll to results
                resultsSection.scrollIntoView({ behavior: 'smooth' });
            }, 1500);
        });
        
        // Download button
        downloadBtn.addEventListener('click', () => {
            // In a real implementation, this would download the actual compressed file
            alert('In a real implementation, this would download the compressed file');
        });
        
        // New file button
        newFileBtn.addEventListener('click', () => {
            // Reset the form
            selectedFile = null;
            fileInput.value = '';
            compressBtn.disabled = true;
            resultsSection.style.display = 'none';
            
            // Reset drop area
            dropArea.innerHTML = `
                <i>📄</i>
                <p><strong>Drag & drop your CV file here</strong></p>
                <p>or</p>
                <input type="file" id="fileInput" accept=".pdf,.docx,.jpg,.jpeg,.png">
                <button class="btn">Select File</button>
                <p class="file-types">Supports: PDF, DOCX, JPG, PNG</p>
            `;
        });
        
        // Helper function to format file size
        function formatFileSize(bytes) {
            if (bytes === 0) return '0 Bytes';
            
            const k = 1024;
            const sizes = ['Bytes', 'KB', 'MB'];
            const i = Math.floor(Math.log(bytes) / Math.log(k));
            
            return parseFloat((bytes / Math.pow(k, i)).toFixed(2)) + ' ' + sizes[i];
        }
    </script>
</body>
</html># cv-maker
