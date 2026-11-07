```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bayern Munich vs Ajax - Official Ticketing | Talanta Sports City</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800;900&display=swap');
        body { font-family: 'Inter', sans-serif; background-color: #0b0f19; color: #ffffff; }
    </style>
</head>
<body class="bg-[#0b0f19] min-h-screen text-white flex flex-col justify-between">

    <!-- TOP ALERT BAR -->
    <header class="bg-gradient-to-r from-red-700 via-red-600 to-black text-white px-4 py-3 shadow-lg">
        <div class="max-w-7xl mx-auto flex flex-col sm:flex-row justify-between items-center gap-2 text-center sm:text-left">
            <div class="flex items-center gap-2 font-black tracking-wider text-sm uppercase">
                <span class="bg-white text-red-600 text-xs px-2 py-0.5 rounded-full animate-pulse">BREAKING NEWS</span>
                <span>MATCHDAY 5 JAN 2027 • TALANTA STADIUM</span>
            </div>
            <div class="text-xs font-semibold uppercase tracking-wider text-red-200">
                Bayern vs Ajax · Standard Tier Open as of <span id="current-time" class="text-white font-bold">7:19 PM</span>
            </div>
        </div>
    </header>

    <!-- HERO / BANNER SECTION -->
    <main class="max-w-7xl mx-auto px-4 py-8 w-full flex-grow">
        
        <!-- Main Banner Card -->
        <div class="relative rounded-2xl overflow-hidden border border-gray-800 shadow-2xl bg-gradient-to-b from-gray-900 to-black p-6 md:p-10 mb-8">
            <div class="absolute inset-0 opacity-25 bg-[radial-gradient(#dc2626_1px,transparent_1px)] [background-size:16px_16px]"></div>
            
            <div class="relative z-10 flex flex-col md:flex-row justify-between items-start md:items-center gap-6">
                <div>
                    <div class="text-red-500 font-extrabold text-sm md:text-base tracking-widest uppercase mb-1">
                        <i class="fa-solid fa-futbol mr-2"></i> Official Club Friendly / Showcase
                    </div>
                    <h1 class="text-4xl md:text-6xl font-black tracking-tight uppercase text-white mb-2">
                        KSh 700 <span class="text-gray-400 text-2xl md:text-3xl font-bold">Tickets</span>
                    </h1>
                    <div class="text-2xl md:text-3xl font-extrabold text-red-500 uppercase tracking-wide animate-pulse">
                        SELLING FAST!
                    </div>
                    <p class="text-gray-400 text-sm md:text-base mt-2 max-w-xl">
                        Bayern Munich takes on Ajax at the state-of-the-art Talanta Sports City, Kenya. Secure your seats before capacity runs out.
                    </p>
                </div>

                <!-- Quick Buy Action Card -->
                <div class="bg-gray-900/90 border border-red-600/50 rounded-xl p-6 backdrop-blur-md w-full md:w-80 shadow-xl">
                    <div class="flex justify-between items-center mb-4">
                        <span class="text-xs font-bold uppercase tracking-wider text-gray-400">Match Date</span>
                        <span class="text-xs font-bold text-red-400 bg-red-950/60 px-2.5 py-1 rounded border border-red-800">5 Jan 2027</span>
                    </div>
                    <div class="text-lg font-black uppercase mb-1 text-white">General Tier</div>
                    <div class="text-3xl font-black text-red-500 mb-4">KSh 700 <span class="text-xs text-gray-400 font-normal">/ ticket</span></div>
                    
                    <button onclick="openCheckout('General Tier', 700)" class="w-full bg-red-600 hover:bg-red-700 transition font-black uppercase tracking-wider py-3 rounded-lg shadow-lg text-white text-center block">
                        Buy Tickets Now
                    </button>
                    <div class="text-[10px] text-gray-400 text-center mt-2">
                        + KSh 50 processing fee. Limit: 10 tickets per user.
                    </div>
                </div>
            </div>
        </div>

        <!-- TICKET TIERS GRID -->
        <h2 class="text-xl font-black uppercase tracking-wider mb-4 flex items-center gap-2">
            <i class="fa-solid fa-ticket text-red-500"></i> Available Stadium Tiers
        </h2>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 mb-8">
            
            <!-- Tier 1: Sold Out / Promo -->
            <div class="bg-gray-900 border border-red-900/40 rounded-xl p-5 flex flex-col justify-between relative overflow-hidden">
                <div class="absolute top-0 right-0 bg-red-600 text-white text-[10px] font-black px-3 py-1 uppercase rounded-bl">Sold Out</div>
                <div>
                    <span class="text-xs font-bold text-gray-400 uppercase">Phase 1 - Standard</span>
                    <div class="text-2xl font-black text-gray-500 line-through mt-1">KSh 700</div>
                </div>
                <div class="mt-6">
                    <div class="text-red-500 font-black text-xl uppercase">SOLD OUT</div>
                    <div class="text-xs text-gray-500 mt-1">Cheapest tier gone</div>
                </div>
            </div>

            <!-- Tier 2: Phase 1 - 1,200 -->
            <div class="bg-gray-900 border border-gray-800 rounded-xl p-5 flex flex-col justify-between hover:border-red-600 transition">
                <div>
                    <span class="text-xs font-bold text-gray-400 uppercase">Phase 1 - Upper Bowl</span>
                    <div class="text-2xl font-black text-white mt-1">KSh 1,200</div>
                </div>
                <div class="mt-6 flex items-end justify-between">
                    <div>
                        <div class="text-2xl font-black text-white">912</div>
                        <div class="text-xs text-gray-400 uppercase font-semibold">seats left</div>
                    </div>
                    <button onclick="openCheckout('Phase 1 - Upper Bowl', 1200)" class="bg-gray-800 hover:bg-red-600 text-white font-bold text-xs uppercase px-4 py-2 rounded transition">
                        Select
                    </button>
                </div>
            </div>

            <!-- Tier 3: Phase 1 - 2,500 -->
            <div class="bg-gray-900 border border-gray-800 rounded-xl p-5 flex flex-col justify-between hover:border-red-600 transition">
                <div>
                    <span class="text-xs font-bold text-gray-400 uppercase">Phase 1 - VIP Tier</span>
                    <div class="text-2xl font-black text-white mt-1">KSh 2,500</div>
                </div>
                <div class="mt-6 flex items-end justify-between">
                    <div>
                        <div class="text-2xl font-black text-white">2,618</div>
                        <div class="text-xs text-gray-400 uppercase font-semibold">seats left</div>
                    </div>
                    <button onclick="openCheckout('Phase 1 - VIP Tier', 2500)" class="bg-gray-800 hover:bg-red-600 text-white font-bold text-xs uppercase px-4 py-2 rounded transition">
                        Select
                    </button>
                </div>
            </div>

            <!-- Tier 4: Level 1 VVIP -->
            <div class="bg-gray-900 border border-gray-800 rounded-xl p-5 flex flex-col justify-between hover:border-red-600 transition">
                <div>
                    <span class="text-xs font-bold text-gray-400 uppercase">Level 1 - VVIP Boxes</span>
                    <div class="text-2xl font-black text-white mt-1">KSh 5,000</div>
                </div>
                <div class="mt-6 flex items-end justify-between">
                    <div>
                        <div class="text-2xl font-black text-white">1,652</div>
                        <div class="text-xs text-gray-400 uppercase font-semibold">seats left</div>
                    </div>
                    <button onclick="openCheckout('Level 1 VVIP', 5000)" class="bg-gray-800 hover:bg-red-600 text-white font-bold text-xs uppercase px-4 py-2 rounded transition">
                        Select
                    </button>
                </div>
            </div>

        </div>

        <!-- NOTIFICATION BANNER -->
        <div class="bg-gray-900/60 border-l-4 border-red-600 p-4 rounded-r-xl flex items-center gap-3 text-sm text-gray-300">
            <i class="fa-solid fa-triangle-exclamation text-red-500 text-lg"></i>
            <div>
                <strong class="text-white">Massive queues expected:</strong> Ticket sales opened at 6:00 PM. Each ticket includes a standard transaction fee. Maximum purchase limit is 10 tickets per transaction.
            </div>
        </div>

    </main>

    <!-- CHECKOUT MODAL -->
    <div id="checkout-modal" class="fixed inset-0 bg-black/80 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
        <div class="bg-gray-900 border border-gray-800 rounded-2xl max-w-md w-full p-6 shadow-2xl relative">
            <button onclick="closeCheckout()" class="absolute top-4 right-4 text-gray-400 hover:text-white text-xl">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <h3 class="text-xl font-black uppercase mb-1 text-white">Complete Your Purchase</h3>
            <p class="text-xs text-gray-400 mb-4">Talanta Sports City Official Ticketing Portal</p>
            
            <div class="bg-black/40 rounded-xl p-4 mb-4 border border-gray-800">
                <div class="flex justify-between text-sm mb-2">
                    <span class="text-gray-400">Selected Tier:</span>
                    <span id="modal-tier" class="font-bold text-white">General Tier</span>
                </div>
                <div class="flex justify-between text-sm mb-2">
                    <span class="text-gray-400">Price per ticket:</span>
                    <span id="modal-price" class="font-bold text-red-500">KSh 700</span>
                </div>
                <div class="flex justify-between text-sm items-center mb-2">
                    <span class="text-gray-400">Quantity:</span>
                    <input type="number" id="ticket-qty" value="1" min="1" max="10" onchange="updateTotal()" class="w-16 bg-gray-800 border border-gray-700 text-center rounded py-1 text-white font-bold">
                </div>
                <hr class="border-gray-800 my-2">
                <div class="flex justify-between text-base font-black">
                    <span>Total Amount:</span>
                    <span id="modal-total" class="text-red-500">KSh 750</span>
                </div>
            </div>

            <form onsubmit="handleCheckoutSubmit(event)" class="space-y-3">
                <div>
                    <label class="block text-xs font-bold text-gray-400 uppercase mb-1">Full Name</label>
                    <input type="text" required placeholder="Enter your full name" class="w-full bg-gray-800 border border-gray-700 rounded-lg px-3 py-2 text-sm text-white focus:outline-none focus:border-red-600">
                </div>
                <div>
                    <label class="block text-xs font-bold text-gray-400 uppercase mb-1">M-Pesa Phone Number</label>
                    <input type="tel" required placeholder="07XX XXX XXX" class="w-full bg-gray-800 border border-gray-700 rounded-lg px-3 py-2 text-sm text-white focus:outline-none focus:border-red-600">
                </div>
                <button type="submit" class="w-full bg-red-600 hover:bg-red-700 text-white font-black uppercase tracking-wider py-3 rounded-lg shadow-lg transition mt-2">
                    Pay with M-Pesa
                </button>
            </form>
        </div>
    </div>

    <!-- SUCCESS MODAL -->
    <div id="success-modal" class="fixed inset-0 bg-black/80 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
        <div class="bg-gray-900 border border-gray-800 rounded-2xl max-w-md w-full p-6 text-center shadow-2xl">
            <div class="w-16 h-16 bg-green-500/20 text-green-500 rounded-full flex items-center justify-center mx-auto mb-4 text-3xl">
                <i class="fa-solid fa-check"></i>
            </div>
            <h3 class="text-2xl font-black uppercase text-white mb-2">STK Push Sent!</h3>
            <p class="text-sm text-gray-300 mb-6">
                Please check your phone and enter your M-Pesa PIN to complete the purchase of <span id="success-details" class="font-bold text-white"></span>. Your tickets will be sent via SMS.
            </p>
            <button onclick="closeSuccess()" class="w-full bg-gray-800 hover:bg-gray-700 text-white font-bold uppercase tracking-wider py-3 rounded-lg transition">
                Done
            </button>
        </div>
    </div>

    <!-- FOOTER -->
    <footer class="border-t border-gray-800 py-6 text-center text-xs text-gray-500">
        <div class="max-w-7xl mx-auto px-4 flex flex-col sm:flex-row justify-between items-center gap-4">
            <div>Official site only: <span class="text-white font-semibold">talantasportscity.com</span></div>
            <div>#BayernAjax #SportsRADAR #TalantaStadium2027</div>
        </div>
    </footer>

    <!-- SCRIPT LOGIC -->
    <script>
        let currentTierPrice = 700;

        function openCheckout(tierName, price) {
            currentTierPrice = price;
            document.getElementById('modal-tier').innerText = tierName;
            document.getElementById('modal-price').innerText = 'KSh ' + price.toLocaleString();
            document.getElementById('ticket-qty').value = 1;
            updateTotal();
            document.getElementById('checkout-modal').classList.remove('hidden');
        }

        function closeCheckout() {
            document.getElementById('checkout-modal').classList.add('hidden');
        }

        function updateTotal() {
            const qty = parseInt(document.getElementById('ticket-qty').value) || 1;
            const fee = 50;
            const total = (currentTierPrice * qty) + fee;
            document.getElementById('modal-total').innerText = 'KSh ' + total.toLocaleString();
        }

        function handleCheckoutSubmit(event) {
            event.preventDefault();
            const qty = document.getElementById('ticket-qty').value;
            const tier = document.getElementById('modal-tier').innerText;
            
            document.getElementById('success-details').innerText = `${qty}x ${tier} tickets`;
            closeCheckout();
            document.getElementById('success-modal').classList.remove('hidden');
        }

        function closeSuccess() {
            document.getElementById('success-modal').classList.add('hidden');
        }
    </script>
</body>
</html>

```# Talanta-tickets
