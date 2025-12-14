<script>
    // Footer component
</script>

<footer class="bg-brand-dark text-white pt-32 pb-12 overflow-hidden relative font-sans">
    <div class="max-w-7xl mx-auto px-4 relative z-10">
        <div class="text-center mb-24">
             <span class="text-[10px] font-bold uppercase tracking-widest border border-white/20 px-3 py-1.5 rounded-full mb-8 inline-block">Start Trading</span>
             <h2 class="text-5xl md:text-7xl font-serif-display mb-6">Get in trader,<br/> we're making profits.</h2>
             <p class="text-gray-400 mb-10 max-w-lg mx-auto text-sm">Join our community of active traders and learn the championship strategies that deliver real results. Start your free trial today.</p>
             
             <div class="flex flex-col sm:flex-row justify-center gap-2 max-w-md mx-auto">
                 <input type="email" placeholder="Enter your email" class="bg-white/5 border border-white/10 rounded-lg px-4 py-3 w-full text-white placeholder-gray-500 focus:outline-none focus:border-amber-500 transition-colors" />
                 <button class="bg-brand-green hover:bg-brand-green-hover text-white px-6 py-3 rounded-lg font-bold whitespace-nowrap transition-colors flex items-center justify-center">
                     Start Free Trial 
                     <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
                 </button>
             </div>
        </div>

        <div class="grid md:grid-cols-4 gap-12 border-t border-white/10 pt-16">
            <div>
                <h3 class="font-bold mb-6">Frequently Asked Questions</h3>
            </div>
            <div class="md:col-span-3 space-y-6">
                {#each ['How is TraderLion different from other trading education platforms?', 'What trading strategies do you teach?', 'Do I need prior trading experience?', 'What brokers does TraderLion work with?', 'How does pricing work?'] as q}
                <div class="border-b border-white/10 pb-6 flex justify-between items-center cursor-pointer group">
                    <span class="text-lg font-light group-hover:text-amber-500 transition-colors">{q}</span>
                    <span class="text-2xl font-light">+</span>
                </div>
                {/each}
            </div>
        </div>

        <div class="grid grid-cols-2 md:grid-cols-5 gap-8 mt-24 text-sm text-gray-400">
            <div>
                <h4 class="text-white font-bold mb-4">Platform</h4>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-white">Daily Analysis</a></li>
                    <li><a href="#" class="hover:text-white">Trade Alerts</a></li>
                    <li><a href="#" class="hover:text-white">Watchlists</a></li>
                    <li><a href="#" class="hover:text-white">Strategy Builder</a></li>
                    <li><a href="#" class="hover:text-white">Risk Calculator</a></li>
                    <li><a href="#" class="hover:text-white">Performance Tracker</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-bold mb-4">Education</h4>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-white">Trading Courses</a></li>
                    <li><a href="#" class="hover:text-white">Chart Reading</a></li>
                    <li><a href="#" class="hover:text-white">Risk Management</a></li>
                    <li><a href="#" class="hover:text-white">Pattern Trading</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-bold mb-4">General</h4>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-white">Pricing</a></li>
                    <li><a href="#" class="hover:text-white">About Us</a></li>
                    <li><a href="#" class="hover:text-white">Founders</a></li>
                    <li><a href="#" class="hover:text-white">Affiliate Program</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-bold mb-4">Resources</h4>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-white">Trading Blog</a></li>
                    <li><a href="#" class="hover:text-white">Market Analysis</a></li>
                    <li><a href="#" class="hover:text-white">Success Stories</a></li>
                    <li><a href="#" class="hover:text-white">Trading Guides</a></li>
                    <li><a href="#" class="hover:text-white">Webinars</a></li>
                    <li><a href="#" class="hover:text-white">vs Investors Underground</a></li>
                    <li><a href="#" class="hover:text-white">vs Warrior Trading</a></li>
                    <li><a href="#" class="hover:text-white">Free Resources</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-bold mb-4">Support</h4>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-white">Contact Us</a></li>
                    <li><a href="#" class="hover:text-white">Community</a></li>
                    <li><a href="#" class="hover:text-white">Help Center</a></li>
                    <li><a href="#" class="hover:text-white">Live Events</a></li>
                </ul>
            </div>
        </div>
        
        <div class="mt-32 text-center relative">
             <h1 class="text-[8rem] md:text-[12rem] font-bold tracking-tighter leading-none text-white select-none">TraderLion</h1>
             <div class="absolute bottom-4 right-0 flex gap-4 text-[10px] text-gray-500 uppercase tracking-widest">
                 <a href="#">Privacy Policy</a>
                 <a href="#">Terms</a>
                 <a href="#">Contact</a>
             </div>
        </div>
    </div>
</footer>
