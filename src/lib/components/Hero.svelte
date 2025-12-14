<script>
    // Hero Component
</script>

<section class="pt-32 pb-16 md:pt-40 md:pb-24 bg-gray-50 relative overflow-hidden font-sans">
    <!-- Grid Background Pattern -->
    <div class="absolute inset-0 z-0 opacity-[0.4]" 
         style="background-image: linear-gradient(#e5e7eb 1px, transparent 1px), linear-gradient(90deg, #e5e7eb 1px, transparent 1px); background-size: 40px 40px;">
    </div>

    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 flex flex-col items-center text-center">
        
        <!-- Headline -->
        <h1 class="text-5xl md:text-7xl lg:text-8xl font-serif-display text-gray-900 leading-[1.1] tracking-tight mb-6 max-w-5xl mx-auto">
            Trade with 
            <span class="inline-flex items-center align-middle mx-1 md:mx-2 relative -top-1 md:-top-2">
                <svg width="60" height="60" viewBox="0 0 24 24" class="w-10 h-10 md:w-16 md:h-16 text-amber-500" fill="currentColor">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M12.2566 21.954C17.929 21.954 22.5274 17.484 22.5274 11.9699C22.5274 6.45586 17.929 1.98584 12.2566 1.98584C6.58422 1.98584 1.98584 6.45586 1.98584 11.9699C1.98584 17.484 6.58422 21.954 12.2566 21.954ZM15.4608 6.63684C15.6167 6.09831 15.0791 5.77985 14.5881 6.1199L7.73395 10.8665C7.20146 11.2352 7.28522 11.9699 7.85977 11.9699H9.66465V11.9563H13.1823L10.3161 12.9394L9.05251 17.303C8.89655 17.8415 9.43412 18.16 9.92517 17.8199L16.7793 13.0734C17.3118 12.7046 17.228 11.9699 16.6535 11.9699H13.9165L15.4608 6.63684Z" fill="currentColor"/>
                </svg>
            </span>
            confidence
        </h1>

        <!-- Subheadline -->
        <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-10 leading-relaxed">
            Master the markets with daily analysis and championship-proven strategies from traders who've achieved real results.
        </p>

        <!-- CTA -->
        <div class="mb-16">
            <a href="#" class="inline-flex items-center justify-center px-8 py-4 border border-transparent text-base font-medium rounded-full text-white bg-brand-green hover:bg-brand-green-hover transition-all shadow-lg hover:shadow-xl transform hover:-translate-y-0.5">
                Start Free Trial
                <svg class="w-5 h-5 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
            </a>
        </div>

        <!-- Video Player / Dashboard Preview -->
        <div class="w-full max-w-5xl mx-auto rounded-lg overflow-hidden shadow-2xl bg-gradient-to-br from-gray-900 to-gray-800 aspect-video relative group cursor-pointer border border-gray-700">
            <!-- Volume Icon -->
            <div class="absolute top-6 right-6 z-20 text-gray-400">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.536 8.464a5 5 0 010 7.072m2.828-9.9a9 9 0 010 12.728M5.586 15H4a1 1 0 01-1-1v-4a1 1 0 011-1h1.586l4.707-4.707C10.923 3.663 12 4.109 12 5v14c0 .891-1.077 1.337-1.707.707L5.586 15z"></path></svg>
            </div>

            <!-- Content -->
            <div class="absolute inset-0 flex flex-col items-center justify-center text-center p-8">
                <!-- Play Button Circle -->
                <div class="w-16 h-16 md:w-20 md:h-20 bg-amber-500/20 backdrop-blur-sm rounded-full flex items-center justify-center mb-6 group-hover:bg-amber-500/30 transition-all border border-amber-500/30">
                    <svg class="w-8 h-8 md:w-10 md:h-10 text-amber-500 fill-current ml-1" viewBox="0 0 24 24">
                        <path d="M8 5v14l11-7z" />
                    </svg>
                </div>

                <!-- Message Text -->
                <h3 class="text-white text-xl md:text-2xl font-medium mb-2">See How Champions Trade</h3>
                <p class="text-gray-400 text-sm md:text-base max-w-lg">
                    Watch our daily market analysis and learn the strategies that generated 1,100% returns.
                </p>
            </div>
            
            <!-- Progress Bar (Fake) -->
            <div class="absolute bottom-0 left-0 right-0 h-1 bg-gray-800">
                <div class="h-full w-1/3 bg-amber-500"></div>
            </div>
        </div>
    </div>
</section>
