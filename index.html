import React, { useState, useEffect } from 'react';
import { 
  Truck, 
  Plane, 
  Ship, 
  Package, 
  Menu, 
  X, 
  Clock, 
  Globe, 
  ShieldCheck, 
  BarChart3, 
  Phone, 
  ArrowRight,
  MessageCircle,
  CheckCircle2,
  ChevronDown
} from 'lucide-react';

const TurboLogistik = () => {
  const [isMenuOpen, setIsMenuOpen] = useState(false);
  const [isScrolled, setIsScrolled] = useState(false);
  const [activeSection, setActiveSection] = useState('home');
  
  // State untuk Tracking System
  const [trackingId, setTrackingId] = useState('');
  const [isLoading, setIsLoading] = useState(false);

  // Efek Sticky Navbar & Scroll Progress
  useEffect(() => {
    const handleScroll = () => {
      setIsScrolled(window.scrollY > 20);
      
      const sections = ['home', 'services', 'about', 'contact'];
      for (const section of sections) {
        const element = document.getElementById(section);
        if (element) {
          const rect = element.getBoundingClientRect();
          if (rect.top <= 150 && rect.bottom >= 150) {
            setActiveSection(section);
          }
        }
      }
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  }, []);

  // Animasi Muncul saat Scroll (Intersection Observer)
  useEffect(() => {
    const observerOptions = {
      threshold: 0.1,
      rootMargin: "0px 0px -50px 0px"
    };

    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('reveal-visible');
        }
      });
    }, observerOptions);

    document.querySelectorAll('.reveal').forEach(el => observer.observe(el));
    return () => observer.disconnect();
  }, []);

  const handleTracking = (e) => {
    e.preventDefault();
    if (!trackingId) return;
    setIsLoading(true);
    setTimeout(() => {
      setIsLoading(false);
      setTrackingId('');
    }, 1500);
  };

  const navLinks = [
    { id: 'home', label: 'Beranda' },
    { id: 'services', label: 'Layanan' },
    { id: 'about', label: 'Tentang' },
    { id: 'contact', label: 'Kontak' }
  ];

  return (
    <div className="font-sans text-slate-800 bg-white selection:bg-blue-600 selection:text-white overflow-x-hidden">
      <style>
        {`
          @import url('https://fonts.googleapis.com/css2?family=Sora:wght@300;400;600;700;800&family=Inter:wght@400;500;600&display=swap');
          
          body { font-family: 'Inter', sans-serif; scroll-behavior: smooth; }
          
          .heading-sora { font-family: 'Sora', sans-serif; font-weight: 800; letter-spacing: -0.03em; }
          .heading-semibold { font-family: 'Sora', sans-serif; font-weight: 700; letter-spacing: -0.02em; }
          
          .reveal {
            opacity: 0;
            transform: translateY(20px);
            transition: all 0.6s cubic-bezier(0.22, 1, 0.36, 1);
          }
          .reveal-visible {
            opacity: 1;
            transform: translateY(0);
          }
          
          .delay-100 { transition-delay: 100ms; }
          .delay-200 { transition-delay: 200ms; }
          .delay-300 { transition-delay: 300ms; }

          @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(-12deg); }
            50% { transform: translateY(-15px) rotate(-10deg); }
          }
          .animate-float { animation: float 5s ease-in-out infinite; }

          /* Hide scrollbar for Chrome, Safari and Opera */
          .no-scrollbar::-webkit-scrollbar { display: none; }
          .no-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
        `}
      </style>
      
      {/* 1. NAVBAR */}
      <nav className={`fixed w-full z-[100] transition-all duration-300 ${isScrolled || isMenuOpen ? 'bg-white shadow-md py-3' : 'bg-transparent py-5'}`}>
        <div className="container mx-auto px-4 md:px-6 flex justify-between items-center">
          <div className="flex items-center gap-2 z-[110]">
            <div className="bg-blue-600 p-1.5 rounded-lg">
              <Truck className="text-white w-5 h-5 md:w-6 md:h-6" />
            </div>
            <span className={`text-xl md:text-2xl heading-sora tracking-tighter ${isScrolled || isMenuOpen ? 'text-[#0A2540]' : 'text-white'}`}>
              TURBO<span className="text-blue-500">LOGISTIK</span>
            </span>
          </div>

          {/* Desktop Menu */}
          <div className="hidden md:flex items-center gap-8">
            {navLinks.map((link) => (
              <a 
                key={link.id}
                href={`#${link.id}`} 
                className={`text-xs font-bold uppercase tracking-widest transition-all relative py-2 group ${activeSection === link.id ? 'text-blue-600' : isScrolled ? 'text-slate-600' : 'text-gray-300'}`}
              >
                {link.label}
                <span className={`absolute bottom-0 left-0 h-0.5 bg-blue-600 transition-all duration-300 ${activeSection === link.id ? 'w-full' : 'w-0 group-hover:w-full'}`}></span>
              </a>
            ))}
            <button className={`px-6 py-2.5 rounded-xl font-bold text-[10px] uppercase tracking-widest transition-all ${isScrolled ? 'bg-blue-600 text-white shadow-lg shadow-blue-600/20' : 'bg-white text-blue-600'}`}>
              Kontak
            </button>
          </div>

          {/* Mobile Toggle */}
          <button 
            className={`md:hidden p-2 z-[110] transition-colors ${isScrolled || isMenuOpen ? 'text-slate-900' : 'text-white'}`} 
            onClick={() => setIsMenuOpen(!isMenuOpen)}
          >
            {isMenuOpen ? <X size={24} /> : <Menu size={24} />}
          </button>
        </div>

        {/* Mobile Menu Drawer */}
        <div className={`fixed inset-0 bg-white z-[100] transition-transform duration-500 ease-in-out md:hidden ${isMenuOpen ? 'translate-x-0' : 'translate-x-full'}`}>
          <div className="flex flex-col items-center justify-center h-full space-y-8 px-6">
            {navLinks.map((link) => (
              <a 
                key={link.id}
                href={`#${link.id}`} 
                className="text-3xl heading-sora text-[#0A2540] hover:text-blue-600 transition-colors"
                onClick={() => setIsMenuOpen(false)}
              >
                {link.label}
              </a>
            ))}
            <button className="w-full max-w-xs bg-blue-600 text-white py-5 rounded-2xl font-bold uppercase tracking-[0.2em] text-xs shadow-xl shadow-blue-600/30">
              Hubungi Kami
            </button>
          </div>
        </div>
      </nav>

      {/* 2. HERO SECTION */}
      <section id="home" className="relative min-h-[90vh] md:min-h-screen flex items-center pt-24 md:pt-20 overflow-hidden bg-[#0A2540]">
        <div className="absolute top-0 right-0 w-full md:w-3/4 h-full bg-gradient-to-bl from-blue-600/20 to-transparent opacity-50 skew-x-0 md:skew-x-12 translate-x-0 md:translate-x-1/4"></div>

        <div className="container mx-auto px-4 md:px-6 relative z-10 grid lg:grid-cols-2 gap-10 md:gap-16 items-center">
          <div className="space-y-6 md:space-y-8 text-white text-center lg:text-left">
            <div className="reveal inline-flex items-center gap-3 px-3 py-1.5 bg-white/5 backdrop-blur-md border border-white/10 rounded-xl text-blue-400 text-[9px] md:text-[10px] font-bold uppercase tracking-[0.2em]">
              <span className="w-1.5 h-1.5 bg-blue-400 rounded-full animate-ping"></span>
              Pioneer Logistik Digital
            </div>
            
            <h1 className="reveal delay-100 text-5xl sm:text-6xl md:text-7xl lg:text-8xl heading-sora leading-[1.1] md:leading-[0.95] tracking-tighter">
              Kirim <br />
              Tanpa <span className="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 via-cyan-300 to-blue-500">Batas.</span>
            </h1>
            
            <p className="reveal delay-200 text-base md:text-xl text-gray-300 max-w-lg mx-auto lg:mx-0 leading-relaxed font-medium">
              Solusi pengiriman cerdas dengan presisi tinggi. Menggabungkan kecepatan turbo dengan keamanan berlapis.
            </p>
            
            <div className="reveal delay-300 flex flex-col sm:flex-row justify-center lg:justify-start gap-4 pt-4">
              <button className="w-full sm:w-auto bg-blue-600 hover:bg-blue-500 text-white px-8 md:px-10 py-4 md:py-5 rounded-xl md:rounded-2xl font-bold text-sm uppercase tracking-widest shadow-2xl shadow-blue-600/30 transition-all active:scale-95">
                Mulai Kirim
              </button>
              <button className="w-full sm:w-auto bg-white/5 hover:bg-white/10 backdrop-blur-md text-white border border-white/10 px-8 md:px-10 py-4 md:py-5 rounded-xl md:rounded-2xl font-bold text-sm uppercase tracking-widest transition-all">
                Cek Tarif
              </button>
            </div>

            {/* Tracking Widget */}
            <div className="reveal delay-300 mt-8 md:mt-12 bg-white/5 backdrop-blur-2xl border border-white/10 p-1.5 md:p-2 rounded-[2rem] md:rounded-[2.5rem] shadow-2xl max-w-md mx-auto lg:mx-0">
              <form onSubmit={handleTracking} className="flex p-1 gap-1.5">
                <input 
                  type="text" 
                  placeholder="No. Resi..."
                  className="flex-1 px-4 md:px-6 py-3.5 md:py-4 rounded-[1.8rem] bg-white/10 text-white placeholder:text-gray-400 focus:outline-none font-bold text-sm border border-transparent w-full"
                  value={trackingId}
                  onChange={(e) => setTrackingId(e.target.value)}
                />
                <button 
                  type="submit"
                  className="bg-blue-600 hover:bg-blue-500 text-white px-6 md:px-8 py-3.5 md:py-4 rounded-[1.8rem] font-extrabold transition-all text-[10px] md:text-xs uppercase tracking-widest whitespace-nowrap"
                >
                  {isLoading ? '...' : 'Lacak'}
                </button>
              </form>
            </div>
          </div>

          <div className="reveal delay-300 hidden lg:block relative">
             <div className="relative animate-float">
                <div className="absolute inset-0 bg-blue-500/20 blur-3xl rounded-full"></div>
                <div className="relative bg-gradient-to-br from-blue-900/50 to-slate-900 border border-white/10 p-1 rounded-[3rem] shadow-3xl">
                    <div className="bg-[#0A2540] rounded-[2.9rem] overflow-hidden p-10 h-[500px] xl:h-[600px] flex items-center justify-center">
                        <Globe className="w-80 h-80 text-blue-500/10 absolute opacity-50" />
                        <Plane className="w-48 xl:w-56 h-auto text-white drop-shadow-2xl relative z-10" />
                        
                        <div className="absolute top-16 right-0 translate-x-1/2 bg-white p-5 rounded-3xl shadow-2xl flex items-center gap-4 border border-blue-50">
                            <div className="bg-blue-100 p-3 rounded-2xl"><Package className="text-blue-600" /></div>
                            <div>
                                <div className="text-[10px] text-gray-400 font-bold uppercase tracking-widest">Delivered</div>
                                <div className="text-lg heading-semibold text-slate-900">12,402+</div>
                            </div>
                        </div>
                    </div>
                </div>
             </div>
          </div>
        </div>

        <div className="absolute bottom-6 left-1/2 -translate-x-1/2 text-white/30 flex flex-col items-center gap-1">
            <span className="text-[9px] uppercase tracking-[0.3em] font-bold">Scroll</span>
            <ChevronDown className="animate-bounce w-4 h-4" />
        </div>
      </section>

      {/* 3. LAYANAN (SERVICES) */}
      <section id="services" className="py-20 md:py-32 bg-white relative">
        <div className="container mx-auto px-4 md:px-6">
          <div className="reveal text-center mb-12 md:mb-24">
            <h2 className="text-blue-600 font-extrabold uppercase tracking-[0.3em] text-[10px] md:text-xs mb-3">Core Services</h2>
            <h3 className="text-3xl md:text-5xl lg:text-6xl heading-sora text-[#0A2540]">Tercepat. Teraman.</h3>
          </div>

          <div className="grid sm:grid-cols-2 lg:grid-cols-4 gap-4 md:gap-8">
            {[
              { icon: Truck, title: 'Kargo Darat', desc: 'Distribusi massal via darat dengan jadwal keberangkatan setiap hari.' },
              { icon: Plane, title: 'Kargo Udara', desc: 'Layanan express antar negara dengan prioritas utama kargo berharga.' },
              { icon: Ship, title: 'Kargo Laut', desc: 'Solusi logistik volume besar dengan rute pelayaran internasional.' },
              { icon: ShieldCheck, title: 'Layanan Aman', desc: 'Asuransi penuh dan penanganan khusus untuk barang pecah belah.' }
            ].map((service, idx) => (
              <div 
                key={idx} 
                className={`reveal delay-${(idx + 1) * 100} group bg-slate-50 p-8 md:p-10 rounded-[2rem] md:rounded-[2.5rem] hover:bg-white hover:shadow-2xl hover:shadow-blue-600/5 transition-all duration-500 border border-transparent hover:border-blue-50 flex flex-col h-full`}
              >
                <div className="bg-white w-14 h-14 md:w-16 md:h-16 rounded-xl md:rounded-2xl flex items-center justify-center mb-6 md:mb-8 shadow-sm group-hover:bg-blue-600 group-hover:scale-110 transition-all duration-500">
                  <service.icon className="w-6 h-6 md:w-8 md:h-8 text-blue-600 group-hover:text-white" />
                </div>
                <h4 className="text-xl md:text-2xl heading-semibold text-slate-900 mb-3 md:mb-4">{service.title}</h4>
                <p className="text-gray-500 text-sm leading-relaxed font-medium flex-1">{service.desc}</p>
                <div className="mt-6 md:mt-8 pt-4 md:pt-6 border-t border-slate-200 flex items-center gap-2 text-blue-600 font-bold text-[10px] md:text-xs uppercase tracking-widest cursor-pointer hover:gap-4 transition-all">
                  Detail <ArrowRight size={14} />
                </div>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* 4. KEUNGGULAN (BENTO GRID STYLE) */}
      <section id="about" className="py-20 md:py-32 bg-slate-50 overflow-hidden">
        <div className="container mx-auto px-4 md:px-6">
          <div className="flex flex-col lg:flex-row gap-12 lg:gap-20 items-center">
            <div className="w-full lg:w-5/12 text-center lg:text-left">
               <div className="reveal space-y-6 md:space-y-8">
                  <h2 className="text-4xl md:text-6xl lg:text-7xl heading-sora text-[#0A2540] leading-tight md:leading-[1.05]">
                    Logistik Masa <br /><span className="text-blue-600 underline decoration-blue-200 underline-offset-8">Depan</span>.
                  </h2>
                  <p className="text-base md:text-lg text-gray-500 font-medium leading-relaxed max-w-lg mx-auto lg:mx-0">
                    Kami tidak hanya mengirim barang; kami memastikan rantai pasok Anda tidak pernah terputus dengan ekosistem digital kami.
                  </p>
                  
                  <div className="space-y-4 md:space-y-6 pt-4 text-left">
                    {[
                        { t: 'Smart Tracking', d: 'Lacak posisi paket hingga ke koordinat GPS terkini.' },
                        { t: 'Eco-Friendly', d: 'Optimasi rute untuk pengurangan emisi karbon.' }
                    ].map((item, i) => (
                        <div key={i} className="flex gap-4 md:gap-5 items-start">
                            <div className="bg-blue-600 p-2 rounded-lg text-white shrink-0"><CheckCircle2 size={16}/></div>
                            <div>
                                <h5 className="heading-semibold text-slate-800 text-sm md:text-base">{item.t}</h5>
                                <p className="text-xs md:text-sm text-gray-500 font-medium">{item.d}</p>
                            </div>
                        </div>
                    ))}
                  </div>
               </div>
            </div>

            <div className="w-full lg:w-7/12 relative">
                <div className="reveal grid grid-cols-1 sm:grid-cols-2 gap-4 md:gap-6">
                    <div className="space-y-4 md:space-y-6">
                        <div className="bg-[#0A2540] p-8 md:p-10 rounded-[2rem] md:rounded-[3rem] text-white h-64 md:h-80 flex flex-col justify-end group transition-transform">
                            <BarChart3 className="text-blue-400 mb-4 md:mb-6 group-hover:scale-110 transition-transform" size={32} md:size={40} />
                            <div className="text-3xl md:text-4xl heading-sora">99%</div>
                            <div className="text-[9px] md:text-[10px] font-bold uppercase tracking-[0.3em] text-gray-400 mt-2">Akurasi Pengiriman</div>
                        </div>
                        <div className="bg-white p-8 md:p-10 rounded-[2rem] md:rounded-[3rem] shadow-xl border border-blue-50 h-56 md:h-64 flex flex-col justify-center">
                            <div className="text-3xl md:text-4xl heading-sora text-blue-600">50+</div>
                            <div className="text-[9px] md:text-[10px] font-bold uppercase tracking-[0.3em] text-slate-400 mt-2">Negara Terjangkau</div>
                        </div>
                    </div>
                    <div className="space-y-4 md:space-y-6 sm:pt-8 md:pt-12">
                         <div className="bg-blue-600 p-8 md:p-10 rounded-[2rem] md:rounded-[3rem] text-white h-64 md:h-72 flex flex-col justify-center shadow-2xl shadow-blue-600/30">
                            <Clock className="text-blue-200 mb-4 md:mb-6" size={32} md:size={40} />
                            <div className="text-3xl md:text-4xl heading-sora">24h</div>
                            <div className="text-[9px] md:text-[10px] font-bold uppercase tracking-[0.3em] text-blue-200 mt-2">Layanan Express</div>
                        </div>
                        <div className="bg-slate-900 p-8 md:p-10 rounded-[2rem] md:rounded-[3rem] text-white h-56 md:h-72 flex items-center justify-center relative overflow-hidden group">
                            <div className="absolute inset-0 bg-blue-600 translate-y-full group-hover:translate-y-0 transition-transform duration-500"></div>
                            <div className="relative z-10 text-center">
                                <MessageCircle size={28} md:size={32} className="mx-auto mb-3 md:mb-4" />
                                <div className="text-[10px] md:text-xs font-bold uppercase tracking-widest">Live Support</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
          </div>
        </div>
      </section>

      {/* 5. LIVE CTA (MOBILE OPTIMIZED) */}
      <section id="contact" className="py-20 md:py-32 bg-white">
        <div className="container mx-auto px-4 md:px-6">
          <div className="reveal bg-[#0A2540] rounded-[2.5rem] md:rounded-[4rem] p-8 md:p-20 text-white flex flex-col lg:flex-row items-center justify-between gap-10 lg:gap-12 relative overflow-hidden">
             <div className="absolute top-0 right-0 w-64 md:w-96 h-64 md:h-96 bg-blue-600 rounded-full blur-[100px] md:blur-[150px] opacity-20 -translate-y-1/2 translate-x-1/2"></div>
             
             <div className="max-w-xl relative z-10 text-center lg:text-left">
                <h2 className="text-3xl md:text-5xl lg:text-6xl heading-sora leading-tight mb-6 md:mb-8">
                  Konsultasikan <br /><span className="text-blue-400">Logistik</span> Anda.
                </h2>
                <p className="text-blue-100 text-base md:text-lg font-medium opacity-80 mb-8 md:mb-10">
                  Dapatkan estimasi harga khusus dalam waktu kurang dari 5 menit.
                </p>
                <div className="flex justify-center lg:justify-start">
                    <div className="flex items-center gap-4 text-left">
                        <div className="bg-blue-500 p-3 md:p-4 rounded-xl md:rounded-2xl shadow-xl shadow-blue-500/20"><Phone size={20} md:size={24} /></div>
                        <div>
                            <div className="text-[9px] md:text-[10px] uppercase tracking-widest text-blue-300 font-bold mb-1">Hubungi Kami</div>
                            <div className="text-lg md:text-xl heading-semibold whitespace-nowrap">1500-TURBO</div>
                        </div>
                    </div>
                </div>
             </div>

             <div className="w-full lg:max-w-md bg-white rounded-[2rem] md:rounded-[3rem] p-8 md:p-10 text-slate-900 relative z-10 shadow-2xl">
                <h4 className="text-xl md:text-2xl heading-semibold mb-6 md:mb-8">Cek Tarif Instant</h4>
                <div className="space-y-4 md:space-y-6">
                    <div className="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div className="space-y-1.5 md:space-y-2">
                            <label className="text-[9px] md:text-[10px] font-bold uppercase tracking-widest text-slate-400">Asal</label>
                            <input type="text" placeholder="Jakarta" className="w-full p-4 bg-slate-50 border-none rounded-xl md:rounded-2xl focus:ring-2 focus:ring-blue-600 font-bold text-sm" />
                        </div>
                        <div className="space-y-1.5 md:space-y-2">
                            <label className="text-[9px] md:text-[10px] font-bold uppercase tracking-widest text-slate-400">Tujuan</label>
                            <input type="text" placeholder="London" className="w-full p-4 bg-slate-50 border-none rounded-xl md:rounded-2xl focus:ring-2 focus:ring-blue-600 font-bold text-sm" />
                        </div>
                    </div>
                    <button className="w-full bg-blue-600 text-white py-4 md:py-5 rounded-xl md:rounded-2xl font-bold uppercase tracking-widest text-[10px] md:text-xs shadow-xl shadow-blue-600/30 hover:bg-[#0A2540] transition-all active:scale-95">
                        Hitung Sekarang
                    </button>
                </div>
             </div>
          </div>
        </div>
      </section>

      {/* 6. FOOTER */}
      <footer className="bg-white pt-16 md:pt-24 pb-8 md:pb-12 border-t border-slate-100">
        <div className="container mx-auto px-4 md:px-6">
          <div className="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-10 md:gap-16 mb-16 md:mb-20">
            <div className="col-span-1">
                <div className="flex items-center gap-2 mb-6 md:mb-8">
                    <div className="bg-blue-600 p-1.5 rounded-lg"><Truck className="text-white w-4 h-4 md:w-5 md:h-5" /></div>
                    <span className="text-lg md:text-xl heading-sora tracking-tighter">TURBO<span className="text-blue-500">LOGISTIK</span></span>
                </div>
                <p className="text-sm text-gray-400 font-medium leading-relaxed">
                    Eksperimen logistik masa depan dengan teknologi otomasi dan kecerdasan buatan.
                </p>
            </div>
            {['Layanan', 'Perusahaan', 'Bantuan'].map((cat, i) => (
                <div key={i}>
                    <h5 className="heading-semibold text-xs md:text-sm uppercase tracking-widest mb-4 md:mb-8 text-slate-900">{cat}</h5>
                    <ul className="space-y-2 md:space-y-4 text-xs md:text-sm font-medium text-gray-500">
                        <li><a href="#" className="hover:text-blue-600 transition-colors">Kargo Udara</a></li>
                        <li><a href="#" className="hover:text-blue-600 transition-colors">E-Commerce</a></li>
                        <li><a href="#" className="hover:text-blue-600 transition-colors">Warehouse</a></li>
                    </ul>
                </div>
            ))}
          </div>
          <div className="pt-8 border-t border-slate-100 flex flex-col md:flex-row justify-between items-center gap-4 text-center md:text-left">
            <div className="text-[9px] md:text-[10px] font-bold uppercase tracking-[0.3em] text-slate-400">&copy; 2025 TURBO LOGISTIK INT.</div>
            <div className="flex gap-6 md:gap-8 text-[9px] md:text-[10px] font-bold uppercase tracking-widest text-slate-400">
                <a href="#" className="hover:text-blue-600 transition-colors">Privacy</a>
                <a href="#" className="hover:text-blue-600 transition-colors">Terms</a>
            </div>
          </div>
        </div>
      </footer>

      {/* Floating Action Button - Mobile Adjusted */}
      <div className="fixed bottom-4 right-4 md:bottom-10 md:right-10 z-[90]">
        <button className="bg-green-500 text-white w-12 h-12 md:w-16 md:h-16 rounded-2xl md:rounded-[1.5rem] shadow-2xl flex items-center justify-center hover:bg-green-600 transition-all active:scale-90">
            <MessageCircle size={24} md:size={32} />
        </button>
      </div>

    </div>
  );
};

export default TurboLogistik;
