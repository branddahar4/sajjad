<!DOCTYPE html>
<html lang="en" class="dark">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>SAJJAD_x_HACKER | Premium Sim Database & Live CNIC Tracker</title>
        <meta name="description" content="SAJJAD_x_HACKER Sim Database 2026 - Ultimate live tracker, CNIC lookup, and mobile number trace tool in Pakistan. Secure, fast, and reliable identity resolution.">
        <meta name="keywords" content="SAJJAD_x_HACKER, sim database online, live tracker pakistan, cnic tracker, trace mobile number, pak sim data, sim owner details, fak official, person tracker, mobile tracker, cnic details">
        <meta name="author" content="SAJJAD_x_HACKER">
        <script src="https://cdn.tailwindcss.com"></script>
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css">
        <script>
            tailwind.config = {
                darkMode: 'class',
                theme: {
                    extend: {
                        colors: {
                            fak: {
                                500: '#00E5FF',
                                600: '#00B8D4',
                                900: '#0B0B0B'
                            }
                        },
                        animation: {
                            'slide-up': 'slideUp 0.3s ease-out',
                            'fade-in': 'fadeIn 0.2s ease-in',
                            'pulse-fast': 'pulse 1s cubic-bezier(0.4, 0, 0.6, 1) infinite',
                        },
                        keyframes: {
                            slideUp: {
                                '0%': { transform: 'translateY(20px)', opacity: '0' },
                                '100%': { transform: 'translateY(0)', opacity: '1' }
                            },
                            fadeIn: {
                                '0%': { opacity: '0' },
                                '100%': { opacity: '1' }
                            }
                        }
                    }
                }
            }
        </script>
        <style>
            body { font-family: 'Segoe UI', system-ui, sans-serif; -webkit-tap-highlight-color: transparent; }
            ::-webkit-scrollbar { width: 8px; }
            ::-webkit-scrollbar-track { background: transparent; }
            ::-webkit-scrollbar-thumb { background: #334155; border-radius: 4px; }
            .dark ::-webkit-scrollbar-thumb { background: #475569; }
            .glass-card { backdrop-filter: blur(12px); -webkit-backdrop-filter: blur(12px); }
            .toast-enter { transform: translateX(100%); opacity: 0; }
            .toast-active { transform: translateX(0); opacity: 1; }

            /* Cyber-punk glitch overlay */
            .cyber-grid {
                background-image: 
                    linear-gradient(rgba(0, 229, 255, 0.03) 1px, transparent 1px),
                    linear-gradient(90deg, rgba(0, 229, 255, 0.03) 1px, transparent 1px);
                background-size: 20px 20px;
            }
        </style>
    <link type="text/css" rel="stylesheet" href="css/style.css"/>
</head>
    <body class="bg-slate-50 text-slate-900 dark:bg-slate-950 dark:text-slate-100 min-h-screen flex flex-col transition-colors duration-300 selection:bg-fak-500 selection:text-white relative">

        <div class="fixed inset-0 cyber-grid pointer-events-none z-0 hidden dark:block"></div>

        <div id="toast-container" class="fixed bottom-4 right-4 z-50 flex flex-col gap-3 pointer-events-none"></div>

        <nav class="sticky top-0 z-40 bg-white/80 dark:bg-slate-900/80 glass-card border-b border-slate-200 dark:border-slate-800">
            <div class="max-w-4xl mx-auto px-4 h-20 flex items-center justify-between">
                <div class="flex items-center gap-3">
                    <img src=" https://cdn.phototourl.com/free/2026-04-15-72eb0a65-d1b4-4140-9a17-f9ac34e519f0.png" alt="FAK LaB Logo" class="w-12 h-12 rounded-full ring-2 ring-fak-500 shadow-[0_0_15px_rgba(0,229,255,0.3)] relative z-10">
                    <div class="relative z-10">
                        <h1 class="text-xl md:text-2xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-fak-500 to-blue-500">SAJJAD_x_HACKER</h1>
                        <p class="text-[10px] text-slate-500 dark:text-fak-500/70 font-mono tracking-widest uppercase">SIM DATABASE</p>
                    </div>
                </div>
                <div class="flex items-center gap-2 md:gap-4 relative z-10">
                    <a href="https://wa.me/923120310972" target="_blank" class="hidden md:flex items-center gap-2 px-4 py-2 bg-green-500 hover:bg-green-600 text-white rounded-full font-semibold transition-all shadow-[0_0_15px_rgba(34,197,94,0.3)] hover:shadow-[0_0_20px_rgba(34,197,94,0.5)]">
                        <i class="bi bi-whatsapp"></i> owner
                    </a>
                    <button onclick="toggleTheme()" class="p-2.5 rounded-full bg-slate-100 dark:bg-slate-800 text-slate-700 dark:text-slate-300 hover:bg-slate-200 dark:hover:bg-slate-700 transition-colors">
                        <i id="theme-icon" class="bi bi-moon-fill text-lg"></i>
                    </button>
                </div>
            </div>
        </nav>

        <main class="flex-grow max-w-4xl w-full mx-auto px-4 py-8 flex flex-col gap-6 relative z-10">

            <div class="flex bg-slate-200 dark:bg-slate-800/50 p-1 rounded-xl">
                <button onclick="switchTab('search')" id="tab-search" class="flex-1 py-3 text-sm md:text-base font-bold rounded-lg bg-white dark:bg-slate-700 shadow-sm transition-all text-fak-600 dark:text-fak-500">
                    <i class="bi bi-crosshair mr-2"></i>Target Trace
                </button>
                <button onclick="switchTab('history')" id="tab-history" class="flex-1 py-3 text-sm md:text-base font-bold rounded-lg text-slate-500 dark:text-slate-400 hover:text-slate-900 dark:hover:text-white transition-all">
                    <i class="bi bi-hdd-network mr-2"></i>Local Logs
                </button>
            </div>

            <section id="view-search" class="animate-fade-in flex flex-col gap-6">
                <div class="bg-white dark:bg-slate-900 border border-slate-200 dark:border-slate-800 rounded-2xl p-6 md:p-8 shadow-[0_8px_30px_rgb(0,0,0,0.12)] dark:shadow-[0_8px_30px_rgba(0,229,255,0.05)] relative overflow-hidden">
                    <div class="absolute top-0 right-0 w-64 h-64 bg-fak-500/10 rounded-full blur-3xl -mr-32 -mt-32 pointer-events-none"></div>

                    <h2 class="text-2xl font-bold mb-2 font-mono flex items-center gap-2">
                        <i class="bi bi-terminal text-fak-500"></i> Initialize Trace
                    </h2>
                    <p class="text-sm text-slate-500 dark:text-slate-400 mb-6 font-mono">Input valid 11-digit MSISDN or 13-digit CNIC to bypass registry nodes.</p>

                    <form id="lookup-form" class="flex flex-col gap-4">
                        <div class="relative">
                            <i class="bi bi-cpu-fill absolute left-4 top-1/2 -translate-y-1/2 text-slate-400 dark:text-fak-500/50"></i>
                            <input type="text" id="lookup-input" required autocomplete="off" placeholder=" 03********" class="w-full bg-slate-50 dark:bg-black/50 border border-slate-300 dark:border-slate-800 text-slate-900 dark:text-fak-500 rounded-xl pl-12 pr-4 py-4 focus:ring-2 focus:ring-fak-500 focus:border-transparent outline-none transition-all text-lg font-mono tracking-widest placeholder:tracking-normal">
                        </div>
                        <button type="submit" id="submit-btn" class="w-full bg-gradient-to-r from-fak-600 to-fak-500 hover:from-fak-500 hover:to-fak-400 text-slate-950 font-extrabold text-lg py-4 rounded-xl shadow-[0_4px_20px_rgba(0,229,255,0.3)] hover:shadow-[0_4px_25px_rgba(0,229,255,0.6)] transform hover:-translate-y-0.5 transition-all flex justify-center items-center gap-2">
                            <i class="bi bi-radar"></i> EXECUTE QUERY
                        </button>
                    </form>
                </div>

                <div id="results-container" class="hidden animate-slide-up"></div>
            </section>

            <section id="view-history" class="hidden flex-col gap-4 animate-fade-in">
                <div class="flex items-center justify-between bg-white dark:bg-slate-900 border border-slate-200 dark:border-slate-800 p-4 rounded-xl shadow-md">
                    <h2 class="text-lg font-bold font-mono"><i class="bi bi-database text-fak-500 mr-2"></i>Encrypted Cache</h2>
                    <button onclick="clearHistory()" class="text-sm text-red-500 hover:text-red-600 dark:text-red-400 dark:hover:text-red-300 font-mono font-semibold px-3 py-1 rounded-md hover:bg-red-50 dark:hover:bg-red-500/10 transition-colors">
                        <i class="bi bi-trash3"></i> PURGE
                    </button>
                </div>
                <div id="history-list" class="flex flex-col gap-3"></div>
            </section>

            <a href="https://whatsapp.com/channel/0029Vb6k15JHLHQbxRTzOo0h" target="_blank" class="mt-4 bg-gradient-to-br from-slate-800 to-slate-900 border border-slate-700 rounded-2xl p-6 shadow-xl hover:border-green-500/50 transition-colors group flex items-center justify-between relative overflow-hidden">
                <div class="absolute inset-0 bg-green-500/5 group-hover:bg-green-500/10 transition-colors pointer-events-none"></div>
                <div class="flex items-center gap-4 relative z-10">
                    <div class="w-12 h-12 bg-black border border-green-500/50 rounded-full flex items-center justify-center text-green-400 text-2xl shadow-[0_0_15px_rgba(34,197,94,0.4)] group-hover:shadow-[0_0_25px_rgba(34,197,94,0.6)] transition-shadow">
                        <i class="bi bi-whatsapp"></i>
                    </div>
                    <div>
                        <h3 class="text-white font-mono font-bold text-lg group-hover:text-green-400 transition-colors">MANI SECURE NETWORK</h3>
                        <p class="text-slate-400 text-sm font-mono text-xs">Establish secure link to HQ for unfiltered databases.</p>
                    </div>
                </div>
                <i class="bi bi-box-arrow-up-right text-slate-500 group-hover:text-green-400 text-xl transition-colors transform group-hover:translate-x-1 group-hover:-translate-y-1 relative z-10"></i>
            </a>

        </main>

        <script>
            // TARGET UPGRADED WORKER
            const WORKER_PROXY_URL = 'https://sim-api.fakcloud.tech/';

            const toastContainer = document.getElementById('toast-container');
            const themeIcon = document.getElementById('theme-icon');
            const htmlDoc = document.documentElement;

            let searchHistory = JSON.parse(localStorage.getItem('fak_history') || '[]');

            function toggleTheme() {
                htmlDoc.classList.toggle('dark');
                const isDark = htmlDoc.classList.contains('dark');
                localStorage.setItem('theme', isDark ? 'dark' : 'light');
                themeIcon.className = isDark ? 'bi bi-moon-stars-fill text-lg' : 'bi bi-sun-fill text-lg';
            }

            function initTheme() {
                const saved = localStorage.getItem('theme');
                if (saved === 'light') {
                    htmlDoc.classList.remove('dark');
                    themeIcon.className = 'bi bi-sun-fill text-lg';
                } else {
                    themeIcon.className = 'bi bi-moon-stars-fill text-lg';
                }
            }

            function showToast(msg, isError = false) {
                const toast = document.createElement('div');
                const bgClass = isError ? 'bg-red-500' : 'bg-slate-900 dark:bg-black border-l-4 border-fak-500';
                const textClass = isError ? 'text-white' : 'text-white dark:text-fak-500';
                const icon = isError ? 'bi-shield-x' : 'bi-shield-check text-fak-500';

                toast.className = flex items-center gap-3 px-4 py-3 rounded-r-xl shadow-lg font-mono text-xs border border-slate-800 transition-all duration-300 toast-enter ${bgClass} ${textClass} pointer-events-auto shadow-[0_0_15px_rgba(0,229,255,0.2)];
                toast.innerHTML = <i class="bi ${icon} text-lg"></i> <span>${msg}</span>;

                toastContainer.appendChild(toast);
                requestAnimationFrame(() => toast.classList.add('toast-active'));

                setTimeout(() => {
                    toast.classList.remove('toast-active');
                    setTimeout(() => toast.remove(), 300);
                }, 3000);
            }

            function switchTab(tab) {
                const viewSearch = document.getElementById('view-search');
                const viewHistory = document.getElementById('view-history');
                const tabSearch = document.getElementById('tab-search');
                const tabHistory = document.getElementById('tab-history');

                const activeClass = ['bg-white', 'dark:bg-slate-700', 'shadow-sm', 'text-fak-600', 'dark:text-fak-500'];
                const inactiveClass = ['text-slate-500', 'dark:text-slate-400', 'hover:text-slate-900', 'dark:hover:text-white', 'bg-transparent'];
                if (tab === 'search') {
                    viewSearch.classList.remove('hidden');
                    viewHistory.classList.add('hidden');
                    viewHistory.classList.remove('flex');

                    tabSearch.classList.add(...activeClass);
                    tabSearch.classList.remove(...inactiveClass);
                    tabHistory.classList.add(...inactiveClass);
                    tabHistory.classList.remove(...activeClass);
                } else {
                    viewSearch.classList.add('hidden');
                    viewHistory.classList.remove('hidden');
                    viewHistory.classList.add('flex');

                    tabHistory.classList.add(...activeClass);
                    tabHistory.classList.remove(...inactiveClass);
                    tabSearch.classList.add(...inactiveClass);
                    tabSearch.classList.remove(...activeClass);
                    renderHistory();
                }
            }

            function copyToClipboard(text, btnElement) {
                const originalHTML = btnElement.innerHTML;

                const successAction = () => {
                    btnElement.innerHTML = '<i class="bi bi-check2-all"></i> Copied';
                    btnElement.classList.replace('text-slate-500', 'text-fak-500');
                    btnElement.classList.replace('dark:text-slate-400', 'dark:text-fak-500');
                    showToast('Data copied to clipboard');
                    setTimeout(() => {
                        btnElement.innerHTML = originalHTML;
                        btnElement.classList.replace('text-fak-500', 'text-slate-500');
                        btnElement.classList.replace('dark:text-fak-500', 'dark:text-slate-400');
                    }, 2000);
                };

                if (navigator.clipboard && window.isSecureContext) {
                    navigator.clipboard.writeText(text).then(successAction).catch(() => fallbackCopy(text, successAction));
                } else {
                    fallbackCopy(text, successAction);
                }
            }

            function fallbackCopy(text, successAction) {
                const textArea = document.createElement("textarea");
                textArea.value = text;
                textArea.style.position = "fixed";
                textArea.style.left = "-999999px";
                document.body.appendChild(textArea);
                textArea.focus();
                textArea.select();
                try {
                    document.execCommand('copy');
                    successAction();
                } catch (err) {
                    showToast('Copy failed. Select text manually', true);
                }
                textArea.remove();
            }

            function addToHistory(number, name) {
                const entry = { number, name: name || 'UNKNOWN_ENTITY', time: new Date().toLocaleString() };
                // Avoid exact duplicates back-to-back
                if (searchHistory.length > 0 && searchHistory[0].number === number) return;

                searchHistory.unshift(entry);
                if (searchHistory.length > 50) searchHistory.pop();
                localStorage.setItem('fak_history', JSON.stringify(searchHistory));
            }

            function clearHistory() {
                searchHistory = [];
                localStorage.removeItem('fak_history');
                renderHistory();
                showToast('Local cache purged');
            }

            function renderHistory() {
                const list = document.getElementById('history-list');
                if (searchHistory.length === 0) {
                    list.innerHTML = <div class="text-center py-8 text-slate-500 dark:text-slate-500 bg-white dark:bg-black/40 rounded-xl border border-slate-200 dark:border-slate-800 font-mono text-sm"><i class="bi bi-x-circle text-2xl mb-2 block text-slate-600"></i>NO LOGS FOUND</div>;
                    return;
                }

                list.innerHTML = searchHistory.map(item => `
                <div class="bg-white dark:bg-black/60 border border-slate-200 dark:border-slate-800 p-4 rounded-xl flex flex-col sm:flex-row sm:items-center justify-between gap-3 hover:border-fak-500/50 transition-all cursor-pointer group" onclick="reRunSearch('${item.number}')">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 rounded-lg bg-slate-100 dark:bg-slate-900 flex items-center justify-center text-slate-400 group-hover:text-fak-500 transition-colors font-bold border border-transparent group-hover:border-fak-500/30">
                            <i class="bi bi-incognito"></i>
            </div>
                        <div>
                            <p class="font-bold text-slate-900 dark:text-fak-500 tracking-wider font-mono">${item.number}</p>
                            <p class="text-xs text-slate-500 dark:text-slate-400 font-mono">${item.name}</p>
            </div>
            </div>
                    <div class="text-[10px] text-slate-400 dark:text-slate-600 flex items-center gap-1 font-mono uppercase tracking-widest">
                        <i class="bi bi-clock-history"></i> ${item.time}
            </div>
            </div>
            `).join('');
            }

            function reRunSearch(num) {
                document.getElementById('lookup-input').value = num;
                switchTab('search');
                document.getElementById('lookup-form').dispatchEvent(new Event('submit'));
            }

            function buildResultCard(apiResponse) {
                // New cyber payload data map
                const meta = apiResponse;
                const records = meta.data?.records || [];

                if (records.length === 0) {
                    return renderError('DECRYPTION FAILED', 'Target exists but data node returned zero readable records.');
                }

                // Create plain text for copying all records
                let copyData = --- Mani LaB SECURE EXPORT ---\n;
                records.forEach((item, i) => {
                    copyData += \n[RECORD ${i+1}]\nPhone: ${item.phone || 'N/A'}\nName: ${item.full_name || 'N/A'}\nCNIC: ${item.cnic || 'N/A'}\nAddress: ${item.address || 'N/A'}\n;
            });
            copyData += \nNode: ${meta.proxy_node || 'UNKNOWN'}\nEOF;

            // HTML generation for individual records
            const recordsHtml = records.map((item, index) => `
                <div class="p-6 flex flex-col gap-4 border-b border-slate-200 dark:border-slate-800 last:border-0 relative">
                    ${records.length > 1 ? <div class="absolute left-0 top-0 bottom-0 w-1 bg-fak-500"></div><div class="text-[10px] font-bold text-fak-500 mb-2 font-mono tracking-widest pl-2">LINKED RECORD _0${index + 1}</div> : ''}
                    ${generateDataRow('MOBILE MSISDN', item.phone)}
                    ${generateDataRow('TARGET IDENTITY', item.full_name)}
                    ${generateDataRow('NATIONAL ID (CNIC)', item.cnic)}
                    ${generateDataRow('REGISTERED LOCATION', item.address)}
            </div>
            `).join('');

            return `
                <div class="bg-white dark:bg-black border border-slate-200 dark:border-slate-800 rounded-2xl overflow-hidden shadow-2xl mt-6 relativ
