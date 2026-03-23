<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>雷德斯減廢科技 | TRT - 工業廢水處理與資源化專家</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;500;700&display=swap');
        
        body {
            font-family: 'Noto Sans TC', sans-serif;
            scroll-behavior: smooth;
        }

        .hero-overlay {
            background: linear-gradient(135deg, rgba(15, 23, 42, 0.9) 0%, rgba(30, 58, 138, 0.7) 100%), 
                        url('https://images.unsplash.com/photo-1581091226825-a6a2a5aee158?auto=format&fit=crop&q=80&w=1600') center/cover;
        }

        .tech-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }

        .gradient-text {
            background: linear-gradient(to right, #38bdf8, #818cf8);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .nav-link {
            position: relative;
        }
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -4px;
            left: 0;
            background-color: #38bdf8;
            transition: width 0.3s;
        }
        .nav-link:hover::after {
            width: 100%;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-900">

    <!-- 導覽列 -->
    <nav class="fixed w-full z-50 bg-white/90 backdrop-blur-md border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20 items-center">
                <div class="flex items-center">
                    <div class="text-2xl font-bold text-blue-900 flex items-center">
                        <i class="fas fa-vial mr-2 text-sky-500"></i>
                        <span>雷德斯減廢科技</span>
                        <span class="text-slate-400 font-light ml-2 text-sm hidden sm:block border-l pl-2 border-slate-300 tracking-widest">TRT</span>
                    </div>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="nav-link font-medium hover:text-sky-600 transition">首頁</a>
                    <a href="#about" class="nav-link font-medium hover:text-sky-600 transition">關於雷德斯</a>
                    <a href="#tech" class="nav-link font-medium hover:text-sky-600 transition">核心技術</a>
                    <a href="#global" class="nav-link font-medium hover:text-sky-600 transition">全球實績</a>
                    <a href="#contact" class="px-6 py-2.5 bg-blue-700 text-white rounded-lg hover:bg-blue-800 transition shadow-lg font-medium">聯繫我們</a>
                </div>
                <div class="md:hidden">
                    <button id="mobile-menu-button" class="text-slate-600 p-2">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- 行動裝置選單 -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t border-slate-100 p-6 space-y-4">
            <a href="#home" class="block text-slate-700 font-medium">首頁</a>
            <a href="#about" class="block text-slate-700 font-medium">關於我們</a>
            <a href="#tech" class="block text-slate-700 font-medium">核心技術</a>
            <a href="#global" class="block text-slate-700 font-medium">全球實績</a>
            <a href="#contact" class="block text-blue-600 font-bold pt-2 border-t">立即諮詢</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-overlay h-screen flex items-center justify-center text-white px-4 relative">
        <div class="max-w-5xl text-center">
            <div class="inline-block px-4 py-1.5 bg-sky-500/20 backdrop-blur-md rounded-full text-sm font-medium mb-6 border border-sky-400/30">
                深耕環工領域 35 年以上專業經驗
            </div>
            <h1 class="text-4xl md:text-7xl font-bold mb-8 leading-tight">
                精準減廢技術<br>
                <span class="gradient-text">重塑水資源價值</span>
            </h1>
            <p class="text-lg md:text-2xl mb-12 text-slate-300 font-light leading-relaxed max-w-3xl mx-auto">
                雷德斯 (TRT) 專注於工業廢水處理藥劑與高效能設備研發，提供從設計、申辦、施工到維運的一站式客製化解決方案。
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-5">
                <a href="#tech" class="px-10 py-4 bg-sky-500 text-white font-bold rounded-xl hover:bg-sky-400 transition shadow-xl text-lg flex items-center justify-center">
                    探索核心技術 <i class="fas fa-arrow-right ml-2 text-sm"></i>
                </a>
                <a href="#contact" class="px-10 py-4 border border-white/30 text-white font-bold rounded-xl hover:bg-white/10 transition backdrop-blur-sm text-lg">
                    索取藥劑樣品
                </a>
            </div>
        </div>
        <!-- 滾動提示 -->
        <div class="absolute bottom-10 left-1/2 -translate-x-1/2 animate-bounce opacity-50">
            <i class="fas fa-chevron-down text-2xl"></i>
        </div>
    </section>

    <!-- 數據概覽 -->
    <section class="py-12 bg-white border-b border-slate-100">
        <div class="max-w-7xl mx-auto px-4 grid grid-cols-2 md:grid-cols-4 gap-8">
            <div class="text-center">
                <div class="text-4xl font-bold text-blue-900 mb-1">35+</div>
                <div class="text-slate-500 text-sm">累積實務經驗 (年)</div>
            </div>
            <div class="text-center">
                <div class="text-4xl font-bold text-blue-900 mb-1">10+</div>
                <div class="text-slate-500 text-sm">獨家研發專利</div>
            </div>
            <div class="text-center">
                <div class="text-4xl font-bold text-blue-900 mb-1">5</div>
                <div class="text-slate-500 text-sm">全球服務國家</div>
            </div>
            <div class="text-center">
                <div class="text-4xl font-bold text-blue-900 mb-1">100%</div>
                <div class="text-slate-500 text-sm">符合環保法規標準</div>
            </div>
        </div>
    </section>

    <!-- 關於我們 -->
    <section id="about" class="py-24 bg-slate-50 overflow-hidden">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex flex-col lg:flex-row items-center gap-16">
                <div class="lg:w-1/2 relative">
                    <div class="absolute -top-10 -left-10 w-64 h-64 bg-sky-100 rounded-full blur-3xl opacity-50 -z-10"></div>
                    <img src="https://images.unsplash.com/photo-1574689232156-977e66ad931e?auto=format&fit=crop&q=80&w=1000" alt="環保設備" class="rounded-3xl shadow-2xl">
                    <div class="absolute -bottom-6 -right-6 bg-white p-6 rounded-2xl shadow-xl flex items-center space-x-4 max-w-xs border border-slate-100">
                        <div class="w-12 h-12 bg-sky-500 rounded-full flex items-center justify-center text-white text-xl">
                            <i class="fas fa-award"></i>
                        </div>
                        <div>
                            <p class="text-xs font-bold text-slate-400 uppercase">卓越品質</p>
                            <p class="text-slate-800 font-bold">台灣唯一大型鉻酸<br>深度純化實績</p>
                        </div>
                    </div>
                </div>
                <div class="lg:w-1/2">
                    <h2 class="text-sky-500 font-bold tracking-widest uppercase mb-4 text-sm">Expertise in Environment</h2>
                    <h3 class="text-3xl md:text-4xl font-bold text-slate-900 mb-6">解決工業廢水的最後一哩路<br>讓排放轉為資源</h3>
                    <p class="text-slate-600 text-lg mb-8 leading-relaxed">
                        雷德斯減廢科技 (TRT) 秉持精益求精的專業技術，致力於應對各項環保法規及日益嚴峻的排放標準。我們自主研發高效工業廢水處理藥劑，並搭配穩固耐用的自動化處理設備，務實解決 COD、重金屬、氰化物、總氮等各類高難度廢水難題。
                    </p>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div class="flex items-center space-x-3 text-slate-700">
                            <i class="fas fa-check-circle text-sky-500"></i>
                            <span class="font-medium">跨領域技術整合 (UF/UV/真空)</span>
                        </div>
                        <div class="flex items-center space-x-3 text-slate-700">
                            <i class="fas fa-check-circle text-sky-500"></i>
                            <span class="font-medium">客製化藥劑配方開發</span>
                        </div>
                        <div class="flex items-center space-x-3 text-slate-700">
                            <i class="fas fa-check-circle text-sky-500"></i>
                            <span class="font-medium">設備耐久設計，穩定運轉數十年</span>
                        </div>
                        <div class="flex items-center space-x-3 text-slate-700">
                            <i class="fas fa-check-circle text-sky-500"></i>
                            <span class="font-medium">自動化控制與友善人機介面</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 核心技術與服務 -->
    <section id="tech" class="py-24 bg-white relative">
        <div class="max-w-7xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-slate-900 mb-4">全方位技術矩陣</h2>
                <p class="text-slate-500 max-w-2xl mx-auto">整合環工、化學、機械與電機，我們為不同產業量身打造最高效益的處理系統。</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- 技術 1 -->
                <div class="bg-slate-50 p-8 rounded-2xl border border-slate-100 tech-card transition-all duration-300">
                    <div class="w-14 h-14 bg-sky-500 text-white rounded-xl flex items-center justify-center mb-6 shadow-lg shadow-sky-200">
                        <i class="fas fa-flask text-2xl"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-4">水處理藥劑設備</h4>
                    <p class="text-slate-600 mb-6 text-sm leading-relaxed">
                        針對不同高低濃度廢水需求，開發高效藥劑。如振動研磨、化學鎳、高 COD 廢液處理，能確保達到排放標準。
                    </p>
                    <ul class="space-y-2 text-slate-500 text-xs">
                        <li><i class="fas fa-caret-right mr-2 text-sky-500"></i> COD 分解劑 (TRT-OC/CaO)</li>
                        <li><i class="fas fa-caret-right mr-2 text-sky-500"></i> 總氮、氨氮、硝酸鹽氮去除劑</li>
                        <li><i class="fas fa-caret-right mr-2 text-sky-500"></i> 客製化藥劑樣品索取</li>
                    </ul>
                </div>

                <!-- 技術 2 -->
                <div class="bg-slate-50 p-8 rounded-2xl border border-slate-100 tech-card transition-all duration-300">
                    <div class="w-14 h-14 bg-blue-600 text-white rounded-xl flex items-center justify-center mb-6 shadow-lg shadow-blue-200">
                        <i class="fas fa-recycle text-2xl"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-4">水回收與鉻酸純化</h4>
                    <p class="text-slate-600 mb-6 text-sm leading-relaxed">
                        台灣唯一大型鉻酸深度純化實績。實現劇毒原物料重複回收使用，大幅節省成本並提升電鍍品質。
                    </p>
                    <ul class="space-y-2 text-slate-500 text-xs">
                        <li><i class="fas fa-caret-right mr-2 text-blue-500"></i> 硬鉻製程鉻酸深度回收</li>
                        <li><i class="fas fa-caret-right mr-2 text-blue-500"></i> 跨領域水回收系統規劃</li>
                        <li><i class="fas fa-caret-right mr-2 text-blue-500"></i> 節能效益與用水量極小化</li>
                    </ul>
                </div>

                <!-- 技術 3 -->
                <div class="bg-slate-50 p-8 rounded-2xl border border-slate-100 tech-card transition-all duration-300">
                    <div class="w-14 h-14 bg-slate-800 text-white rounded-xl flex items-center justify-center mb-6 shadow-lg shadow-slate-400">
                        <i class="fas fa-filter text-2xl"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-4">薄膜分離與污泥減量</h4>
                    <p class="text-slate-600 mb-6 text-sm leading-relaxed">
                        導入奈米級物料分離技術，搭配加熱型板框擠壓與高真空，將污泥含水率降至極低，解決廢棄物處理難題。
                    </p>
                    <ul class="space-y-2 text-slate-500 text-xs">
                        <li><i class="fas fa-caret-right mr-2 text-slate-800"></i> UF 膜/RO/奈米級物料分離</li>
                        <li><i class="fas fa-caret-right mr-2 text-slate-800"></i> 生物污泥乾燥減量系統</li>
                        <li><i class="fas fa-caret-right mr-2 text-slate-800"></i> 電化學與真空濃縮整合</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- 全球實績 -->
    <section id="global" class="py-24 bg-slate-900 text-white">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-end mb-16 gap-6">
                <div>
                    <h2 class="text-3xl font-bold mb-4">全球實績案例</h2>
                    <p class="text-slate-400">憑藉專業技術，雷德斯 TRT 成功在海內外完成了眾多重要的環境工程專案。</p>
                </div>
                <div class="flex space-x-2">
                    <span class="px-3 py-1 bg-white/10 rounded text-xs">USA</span>
                    <span class="px-3 py-1 bg-white/10 rounded text-xs">Oman</span>
                    <span class="px-3 py-1 bg-white/10 rounded text-xs">India</span>
                    <span class="px-3 py-1 bg-white/10 rounded text-xs">Indonesia</span>
                    <span class="px-3 py-1 bg-white/10 rounded text-xs">China</span>
                </div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="group relative overflow-hidden rounded-2xl">
                    <img src="https://images.unsplash.com/photo-1541888941255-2122676f30e5?auto=format&fit=crop&q=80&w=800" class="w-full h-64 object-cover transition duration-500 group-hover:scale-110">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/40 to-transparent p-6 flex flex-col justify-end">
                        <p class="text-sky-400 text-xs font-bold mb-2">美國南加州</p>
                        <h5 class="font-bold text-lg">農膜回收製程回收系統</h5>
                        <p class="text-slate-300 text-xs mt-2 line-clamp-2">包含肥料、生物污泥及大量砂土及水回收處理工程。</p>
                    </div>
                </div>
                <div class="group relative overflow-hidden rounded-2xl">
                    <img src="https://images.unsplash.com/photo-1584467735815-f778f274e296?auto=format&fit=crop&q=80&w=800" class="w-full h-64 object-cover transition duration-500 group-hover:scale-110">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/40 to-transparent p-6 flex flex-col justify-end">
                        <p class="text-sky-400 text-xs font-bold mb-2">阿曼馬斯喀特</p>
                        <h5 class="font-bold text-lg">熱浸鍍鋅產線工業廢液處理</h5>
                        <p class="text-slate-300 text-xs mt-2 line-clamp-2">高 COD、脫脂、油污、鋅離子等複雜來源廢水設備工程。</p>
                    </div>
                </div>
                <div class="group relative overflow-hidden rounded-2xl">
                    <img src="https://images.unsplash.com/photo-1565374395427-440183182643?auto=format&fit=crop&q=80&w=800" class="w-full h-64 object-cover transition duration-500 group-hover:scale-110">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/40 to-transparent p-6 flex flex-col justify-end">
                        <p class="text-sky-400 text-xs font-bold mb-2">印度清奈</p>
                        <h5 class="font-bold text-lg">鞋業製程硬鉻電鍍廢水處理</h5>
                        <p class="text-slate-300 text-xs mt-2 line-clamp-2">處理硬鉻電鍍、溶劑色料、高 COD 複雜水體。客戶：豐泰集團。</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 聯繫我們 -->
    <section id="contact" class="py-24 bg-slate-50 relative">
        <div class="max-w-7xl mx-auto px-4">
            <div class="bg-white rounded-3xl shadow-2xl overflow-hidden flex flex-col lg:flex-row border border-slate-100">
                <div class="lg:w-2/5 bg-blue-900 text-white p-12 flex flex-col justify-between">
                    <div>
                        <h3 class="text-3xl font-bold mb-6">開始您的<br>資源化轉型</h3>
                        <p class="text-blue-200 mb-12">我們的專家團隊隨時準備為您提供最精準的廢水處理與藥劑規劃方案。</p>
                        
                        <div class="space-y-6">
                            <div class="flex items-start space-x-4">
                                <i class="fas fa-map-marker-alt text-sky-400 mt-1"></i>
                                <div>
                                    <p class="font-bold">公司地址</p>
                                    <p class="text-blue-200 text-sm">新北市三重區溪尾街126巷15號</p>
                                </div>
                            </div>
                            <div class="flex items-start space-x-4">
                                <i class="fas fa-phone-alt text-sky-400 mt-1"></i>
                                <div>
                                    <p class="font-bold">諮詢專線</p>
                                    <p class="text-blue-200 text-sm">02-2286-6693</p>
                                </div>
                            </div>
                            <div class="flex items-start space-x-4">
                                <i class="fab fa-line text-sky-400 mt-1"></i>
                                <div>
                                    <p class="font-bold">LINE ID</p>
                                    <p class="text-blue-200 text-sm">trt9002</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="mt-12 pt-12 border-t border-white/10">
                        <p class="text-xs text-blue-300">統一編號: 12755761</p>
                    </div>
                </div>

                <div class="lg:w-3/5 p-12">
                    <form class="space-y-6">
                        <div class="grid md:grid-cols-2 gap-6">
                            <div>
                                <label class="block text-xs font-bold text-slate-400 uppercase mb-2">聯絡姓名</label>
                                <input type="text" class="w-full px-4 py-3 bg-slate-50 border border-slate-200 rounded-lg focus:ring-2 focus:ring-sky-500 outline-none" placeholder="您的稱呼">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-400 uppercase mb-2">公司名稱</label>
                                <input type="text" class="w-full px-4 py-3 bg-slate-50 border border-slate-200 rounded-lg focus:ring-2 focus:ring-sky-500 outline-none" placeholder="貴公司簡稱">
                            </div>
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-400 uppercase mb-2">需求類型</label>
                            <select class="w-full px-4 py-3 bg-slate-50 border border-slate-200 rounded-lg focus:ring-2 focus:ring-sky-500 outline-none">
                                <option>工業廢水處理藥劑諮詢</option>
                                <option>水回收系統規劃 (含鉻酸純化)</option>
                                <option>廢水處理設備新設/修改</option>
                                <option>索取藥劑樣品</option>
                                <option>其他環保工程諮詢</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-400 uppercase mb-2">問題或現狀描述</label>
                            <textarea rows="4" class="w-full px-4 py-3 bg-slate-50 border border-slate-200 rounded-lg focus:ring-2 focus:ring-sky-500 outline-none" placeholder="請描述您的廢水來源或目前遇到的技術瓶頸"></textarea>
                        </div>
                        <button type="submit" class="w-full py-4 bg-sky-500 text-white font-bold rounded-lg hover:bg-sky-600 transition shadow-lg text-lg">
                            送出諮詢申請
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-950 text-slate-500 py-16">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <div class="text-white text-2xl font-bold mb-6 flex items-center justify-center">
                <i class="fas fa-vial text-sky-500 mr-2"></i> TRT 雷德斯減廢科技
            </div>
            <p class="max-w-xl mx-auto mb-10 text-sm leading-relaxed">
                專精於工業製程廢水處理藥劑、設備及深度資源化回收技術。跨領域整合環工、化學、機械與電機，為全球客戶創造更大的商業價值。
            </p>
            <div class="border-t border-white/5 pt-10 text-xs">
                &copy; 2026 台灣雷德斯減廢科技有限公司 Taiwan Redes Technology Co., Ltd. 版權所有 <br>
                241080 新北市三重區溪尾街126巷15號 | TEL: 02-2286-6693
            </div>
        </div>
    </footer>

    <script>
        // 行動裝置選單
        const btn = document.getElementById('mobile-menu-button');
        const menu = document.getElementById('mobile-menu');
        btn.addEventListener('click', () => menu.classList.toggle('hidden'));

        // 導覽列捲動效果
        window.addEventListener('scroll', () => {
            const nav = document.querySelector('nav');
            if (window.scrollY > 50) {
                nav.classList.add('shadow-md');
            } else {
                nav.classList.remove('shadow-md');
            }
        });

        // 模擬表單提交
        document.querySelector('form').addEventListener('submit', (e) => {
            e.preventDefault();
            const modal = document.createElement('div');
            modal.className = 'fixed inset-0 bg-black/50 backdrop-blur-sm flex items-center justify-center z-[100] px-4';
            modal.innerHTML = `
                <div class="bg-white p-8 rounded-2xl shadow-2xl max-w-sm w-full text-center">
                    <div class="w-16 h-16 bg-sky-100 text-sky-600 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-paper-plane text-2xl"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-2 text-slate-900">諮詢已成功送出</h4>
                    <p class="text-slate-500 text-sm">感謝您的聯繫！雷德斯專業團隊將於 24 小時內安排專員回覆您的需求。</p>
                    <button class="mt-6 w-full py-3 bg-sky-500 text-white rounded-lg font-bold" onclick="this.parentElement.parentElement.remove()">確定</button>
                </div>
            `;
            document.body.appendChild(modal);
        });
    </script>
</body>
</html>
