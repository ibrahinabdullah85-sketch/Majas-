import React, { useState, useEffect } from 'react';
import { Play, Home, Star, ArrowRight, CheckCircle, XCircle, Award, BookOpen, Map, RefreshCw } from 'lucide-react';

export default function App() {
  // Application State
  const [screen, setScreen] = useState('home'); // home, map, materi, quiz, result
  const [activeMateri, setActiveMateri] = useState(null);
  const [stars, setStars] = useState(0);
  const [materiProgress, setMateriProgress] = useState({
    personifikasi: false,
    asosiasi: false,
    hiperbola: false,
    metafora: false
  });
  
  // Quiz State
  const [currentQIndex, setCurrentQIndex] = useState(0);
  const [currentMiniQIndex, setCurrentMiniQIndex] = useState(0);
  const [score, setScore] = useState(0);
  const [showFeedback, setShowFeedback] = useState(false);
  const [feedbackData, setFeedbackData] = useState(null);
  const [quizAnswers, setQuizAnswers] = useState({ correct: 0, wrong: 0 });

  const materiData = {
    personifikasi: {
      title: "Majas Personifikasi",
      icon: "🍃🗣️",
      color: "bg-green-400",
      pengertian: "Majas personifikasi adalah majas yang memberikan sifat atau perilaku manusia kepada benda mati, hewan, atau alam.",
      ciri: [
        "Benda atau alam digambarkan seolah-olah dapat melakukan tindakan manusia.",
        "Menggunakan kata-kata yang menggambarkan perilaku manusia."
      ],
      contoh: [
        { text: "Angin berbisik di antara pepohonan.", img: "🌬️💬🌳" },
        { text: "Matahari tersenyum menyambut pagi.", img: "☀️😊🌄" },
        { text: "Daun-daun menari tertiup angin.", img: "🍃💃🌬️" }
      ],
      miniQuiz: [
        {
          question: "Kalimat manakah yang menggunakan majas personifikasi?",
          options: [
            "Tas itu seberat gunung.",
            "Daun-daun menari tertiup angin."
          ],
          answer: 1,
          explanation: "Benar! Daun tidak bisa menari seperti manusia, ini adalah personifikasi."
        },
        {
          question: "Mana di bawah ini yang merupakan majas personifikasi?",
          options: [
            "Angin berbisik memanggil namaku.",
            "Suaranya merdu bagai burung."
          ],
          answer: 0,
          explanation: "Tepat sekali! Angin seolah-olah bisa berbisik seperti manusia."
        },
        {
          question: "Pilih kalimat yang mengandung majas personifikasi:",
          options: [
            "Matahari tersenyum padaku pagi ini.",
            "Dia anak emas di keluarganya."
          ],
          answer: 0,
          explanation: "Benar! Matahari diberikan sifat manusia yaitu 'tersenyum'."
        }
      ]
    },
    asosiasi: {
      title: "Majas Asosiasi",
      icon: "👸🌕",
      color: "bg-purple-400",
      pengertian: "Majas asosiasi membandingkan dua hal yang berbeda tetapi dianggap memiliki kesamaan, biasanya menggunakan kata seperti, bagai, bagaikan, laksana, atau bak.",
      ciri: [
        "Membandingkan dua hal yang berbeda.",
        "Menggunakan kata pembanding (seperti, bagai, dll).",
        "Menunjukkan persamaan sifat atau keadaan."
      ],
      contoh: [
        { text: "Wajahnya bersinar seperti bulan.", img: "👧✨🌝" },
        { text: "Adik berlari laksana kijang.", img: "👦🏃🦌" },
        { text: "Suaranya merdu bagaikan kicauan burung.", img: "🎶🎵🐦" }
      ],
      miniQuiz: [
        {
          question: "Kalimat manakah yang menggunakan majas asosiasi?",
          options: [
            "Adik berlari laksana kijang.",
            "Angin menyapaku pagi ini."
          ],
          answer: 0,
          explanation: "Benar! Ada kata pembanding 'laksana' yang membandingkan lari adik dengan kijang."
        },
        {
          question: "Mana di bawah ini yang merupakan majas asosiasi?",
          options: [
            "Wajahnya bersinar seperti bulan.",
            "Tasnya seberat gunung."
          ],
          answer: 0,
          explanation: "Tepat sekali! Menggunakan kata 'seperti' untuk membandingkan wajah dan bulan."
        },
        {
          question: "Pilih kalimat yang mengandung majas asosiasi:",
          options: [
            "Ayah adalah tulang punggung keluarga.",
            "Suaranya merdu bagaikan kicauan burung."
          ],
          answer: 1,
          explanation: "Benar! Ada kata pembanding 'bagaikan'."
        }
      ]
    },
    hiperbola: {
      title: "Majas Hiperbola",
      icon: "🎒⛰️",
      color: "bg-red-400",
      pengertian: "Majas hiperbola adalah majas yang mengungkapkan sesuatu secara berlebihan untuk memberikan penekanan atau kesan yang kuat.",
      ciri: [
        "Menggunakan ungkapan yang berlebihan.",
        "Tidak selalu dimaksudkan secara harfiah (sebenarnya).",
        "Bertujuan memperkuat kesan atau perasaan."
      ],
      contoh: [
        { text: "Aku sudah menunggumu selama seribu tahun.", img: "⏳💀🕰️" },
        { text: "Suaranya menggelegar membelah langit.", img: "🗣️⚡☁️" },
        { text: "Tas itu beratnya seperti membawa gunung.", img: "🎒😩⛰️" }
      ],
      miniQuiz: [
        {
          question: "Kalimat manakah yang menggunakan majas hiperbola?",
          options: [
            "Bunga mawar itu merah.",
            "Suaranya menggelegar membelah langit."
          ],
          answer: 1,
          explanation: "Hebat! 'Membelah langit' adalah ungkapan yang sangat berlebihan (hiperbola)."
        },
        {
          question: "Mana di bawah ini yang merupakan majas hiperbola?",
          options: [
            "Air matanya mengalir menganak sungai.",
            "Daun melambai tertiup angin."
          ],
          answer: 0,
          explanation: "Tepat sekali! Air mata yang 'menganak sungai' adalah ungkapan melebih-lebihkan."
        },
        {
          question: "Pilih kalimat yang mengandung majas hiperbola:",
          options: [
            "Aku sudah menunggumu seribu tahun lamanya.",
            "Bibirnya merah seperti stroberi."
          ],
          answer: 0,
          explanation: "Benar! Menunggu seribu tahun adalah ungkapan yang sengaja dilebih-lebihkan."
        }
      ]
    },
    metafora: {
      title: "Majas Metafora",
      icon: "⭐👨‍🎓",
      color: "bg-blue-400",
      pengertian: "Majas metafora adalah majas yang membandingkan dua hal secara langsung tanpa menggunakan kata pembanding seperti 'bagai' atau 'bagaikan'.",
      ciri: [
        "Menggunakan perbandingan langsung.",
        "Menggambarkan sesuatu dengan istilah lain.",
        "Memiliki makna kiasan."
      ],
      contoh: [
        { text: "Rina adalah bintang kelas.", img: "👧⭐🏫" },
        { text: "Ayah adalah tulang punggung keluarga.", img: "👨💪🏠" },
        { text: "Dia menjadi buah hati ibunya.", img: "👶❤️👩" }
      ],
      miniQuiz: [
        {
          question: "Kalimat manakah yang menggunakan majas metafora?",
          options: [
            "Rina adalah bintang kelas.",
            "Rina rajin belajar."
          ],
          answer: 0,
          explanation: "Tepat sekali! 'Bintang kelas' adalah perbandingan langsung untuk anak yang berprestasi."
        },
        {
          question: "Mana di bawah ini yang merupakan majas metafora?",
          options: [
            "Berlari laksana kijang.",
            "Ayah adalah tulang punggung keluarga."
          ],
          answer: 1,
          explanation: "Benar! 'Tulang punggung' digunakan sebagai kiasan untuk penopang keluarga tanpa kata pembanding."
        },
        {
          question: "Pilih kalimat yang mengandung majas metafora:",
          options: [
            "Dia adalah buah hati keluarganya.",
            "Suaranya menggelegar membelah langit."
          ],
          answer: 0,
          explanation: "Tepat sekali! 'Buah hati' adalah kiasan langsung untuk anak kesayangan."
        }
      ]
    }
  };

  const finalQuizData = [
    // Personifikasi
    { q: "Angin malam berbisik di telingaku. Jenis majas pada kalimat tersebut adalah ...", o: ["Metafora", "Hiperbola", "Personifikasi", "Asosiasi"], a: 2, exp: "Angin digambarkan seolah-olah dapat berbisik seperti manusia (Personifikasi)." },
    { q: "Pena itu menari-nari di atas kertas. Jenis majas pada kalimat tersebut adalah ...", o: ["Personifikasi", "Metafora", "Hiperbola", "Asosiasi"], a: 0, exp: "Pena adalah benda mati yang digambarkan bisa 'menari' layaknya manusia." },
    { q: "Matahari tersenyum menyambut pagi hari. Jenis majas pada kalimat tersebut adalah ...", o: ["Asosiasi", "Personifikasi", "Metafora", "Hiperbola"], a: 1, exp: "Matahari tidak bisa tersenyum secara nyata, ini adalah sifat manusia yang diberikan ke alam." },
    { q: "Daun-daun melambai tertiup angin kencang. Jenis majas pada kalimat tersebut adalah ...", o: ["Hiperbola", "Metafora", "Asosiasi", "Personifikasi"], a: 3, exp: "Daun yang melambai adalah contoh majas personifikasi." },
    // Asosiasi
    { q: "Rambutnya hitam seperti malam. Jenis majas pada kalimat tersebut adalah ...", o: ["Hiperbola", "Asosiasi", "Metafora", "Personifikasi"], a: 1, exp: "Kalimat membandingkan rambut dengan malam menggunakan kata 'seperti'." },
    { q: "Semangatnya berkobar laksana api. Jenis majas pada kalimat tersebut adalah ...", o: ["Asosiasi", "Personifikasi", "Hiperbola", "Metafora"], a: 0, exp: "Terdapat kata pembanding 'laksana' yang merupakan ciri khas majas asosiasi." },
    { q: "Wajahnya bersinar bagaikan bulan purnama. Jenis majas pada kalimat tersebut adalah ...", o: ["Personifikasi", "Asosiasi", "Metafora", "Hiperbola"], a: 1, exp: "Menggunakan kata 'bagaikan' untuk membandingkan wajah dengan bulan purnama." },
    { q: "Adik berlari bak kijang yang ketakutan. Jenis majas pada kalimat tersebut adalah ...", o: ["Hiperbola", "Metafora", "Personifikasi", "Asosiasi"], a: 3, exp: "Kata 'bak' digunakan untuk membandingkan cara adik berlari dengan kijang." },
    // Hiperbola
    { q: "Aku sudah memanggilmu seribu kali. Jenis majas pada kalimat tersebut adalah ...", o: ["Metafora", "Asosiasi", "Personifikasi", "Hiperbola"], a: 3, exp: "Ungkapan 'seribu kali' digunakan secara berlebihan (Hiperbola)." },
    { q: "Suaranya menggelegar membelah langit. Jenis majas pada kalimat tersebut adalah ...", o: ["Hiperbola", "Personifikasi", "Asosiasi", "Metafora"], a: 0, exp: "Membelah langit adalah ungkapan berlebihan untuk menggambarkan suara yang sangat keras." },
    { q: "Air matanya mengalir menganak sungai. Jenis majas pada kalimat tersebut adalah ...", o: ["Asosiasi", "Hiperbola", "Personifikasi", "Metafora"], a: 1, exp: "Menangis hingga air matanya menjadi seperti sungai adalah hal yang dilebih-lebihkan." },
    { q: "Tas ini beratnya seperti membawa gunung. Jenis majas pada kalimat tersebut adalah ...", o: ["Personifikasi", "Metafora", "Hiperbola", "Asosiasi"], a: 2, exp: "Menyamakan berat tas dengan gunung adalah bentuk hiperbola (melebih-lebihkan)." },
    // Metafora
    { q: "Dia adalah bintang kelas di sekolah ini. Jenis majas pada kalimat tersebut adalah ...", o: ["Metafora", "Personifikasi", "Asosiasi", "Hiperbola"], a: 0, exp: "Seseorang disebut 'bintang kelas' secara langsung (tanpa kata pembanding) untuk menggambarkan siswa berprestasi." },
    { q: "Ayah adalah tulang punggung keluarga. Jenis majas pada kalimat tersebut adalah ...", o: ["Hiperbola", "Asosiasi", "Metafora", "Personifikasi"], a: 2, exp: "Tulang punggung adalah kiasan untuk orang yang menjadi penopang utama." },
    { q: "Adik telah menjadi buah hati ibu sejak lahir. Jenis majas pada kalimat tersebut adalah ...", o: ["Personifikasi", "Metafora", "Hiperbola", "Asosiasi"], a: 1, exp: "'Buah hati' adalah perbandingan langsung (metafora) yang berarti anak kesayangan." }
  ];

  const playSound = (type) => {
    // In a real app we'd play actual audio objects here
    // For this environment, we rely on visual feedback
  };

  const handleMiniQuiz = (materiKey, selectedOptionIdx) => {
    const data = materiData[materiKey];
    const currentQuiz = data.miniQuiz[currentMiniQIndex % data.miniQuiz.length];
    
    if (selectedOptionIdx === currentQuiz.answer) {
      setFeedbackData({ isCorrect: true, text: currentQuiz.explanation });
      if (!materiProgress[materiKey]) {
        setStars(stars + 1);
        setMateriProgress({...materiProgress, [materiKey]: true});
      }
    } else {
      setFeedbackData({ isCorrect: false, text: "Oopss! Kurang tepat. Coba baca lagi materinya dan jawab pertanyaan yang baru ya!" });
    }
    setShowFeedback(true);
  };

  const handleQuizAnswer = (selectedIdx) => {
    const question = finalQuizData[currentQIndex];
    const isCorrect = selectedIdx === question.a;
    
    setFeedbackData({ 
      isCorrect: isCorrect, 
      text: question.exp 
    });
    
    if (isCorrect) {
      setScore(score + 1);
      setQuizAnswers({ ...quizAnswers, correct: quizAnswers.correct + 1 });
    } else {
      setQuizAnswers({ ...quizAnswers, wrong: quizAnswers.wrong + 1 });
    }
    
    setShowFeedback(true);
  };

  const nextQuizQuestion = () => {
    setShowFeedback(false);
    if (currentQIndex + 1 < finalQuizData.length) {
      setCurrentQIndex(currentQIndex + 1);
    } else {
      setScreen('result');
    }
  };

  const resetQuiz = () => {
    setCurrentQIndex(0);
    setScore(0);
    setQuizAnswers({ correct: 0, wrong: 0 });
    setScreen('quiz');
  };

  const TopNav = () => (
    <div className="bg-white/90 backdrop-blur-md p-3 flex justify-between items-center border-b-2 border-yellow-300 shadow-sm z-10 sticky top-0 shrink-0">
      <button 
        onClick={() => setScreen('home')}
        className="flex items-center gap-1 bg-sky-400 hover:bg-sky-500 text-white px-3 py-1.5 rounded-full font-bold shadow-md transition-transform active:scale-95 text-sm"
      >
        <Home size={16} /> Beranda
      </button>
      <div className="flex items-center gap-1 bg-yellow-300 text-yellow-900 px-3 py-1.5 rounded-full font-extrabold shadow-md border-2 border-yellow-500 text-sm">
        <Star className="text-yellow-500 fill-current" size={16} /> 
        {stars}
      </div>
    </div>
  );

  const renderHome = () => (
    <div className="flex-1 flex flex-col items-center justify-center p-5 text-center bg-gradient-to-b from-sky-300 to-sky-100">
      <div className="bg-white p-4 rounded-3xl shadow-xl border-4 border-white transform rotate-2 animate-bounce-slow mb-6 w-full">
        <h1 className="text-3xl font-black text-transparent bg-clip-text bg-gradient-to-r from-blue-600 to-purple-600 mb-1 leading-tight">
          SELAMAT DATANG DI <br/> KOTA MAJAS!
        </h1>
      </div>
      
      <p className="text-base font-bold text-gray-700 mb-6 bg-white/60 p-3 rounded-2xl shadow-sm w-full">
        "Belajar Bahasa Indonesia dengan Cara yang Seru!"
      </p>

      <div className="relative mb-8">
        <div className="text-7xl mb-2">👦🧭👧</div>
        <div className="absolute -top-4 -right-2 text-3xl animate-bounce">✨</div>
      </div>

      <div className="bg-yellow-100 border-l-8 border-yellow-500 p-4 rounded-xl w-full mb-8 shadow-md text-left text-sm">
        <p className="text-gray-800 font-medium">
          <strong>👨‍🏫 Pak Guru:</strong> "Halo, Penjelajah! Hari ini kita akan menjelajahi dunia majas. Siapkan semangatmu!"
        </p>
      </div>

      <button 
        onClick={() => setScreen('map')}
        className="group relative inline-flex items-center justify-center px-6 py-3 font-bold text-white bg-green-500 rounded-full shadow-xl hover:bg-green-600 active:scale-95 transition-all text-lg w-full"
      >
        <Play className="mr-2 group-hover:animate-pulse" size={24} fill="currentColor" />
        MULAI
      </button>
    </div>
  );

  const renderMap = () => (
    <div className="flex-1 flex flex-col p-4 bg-gradient-to-b from-blue-100 to-green-100 relative">
      <div className="text-center mb-6">
        <h2 className="text-xl font-black text-blue-800 uppercase tracking-wider bg-white inline-block px-6 py-2 rounded-full shadow-md border-4 border-blue-200 mt-2">
          Peta Kota Majas
        </h2>
      </div>

      <div className="flex flex-col gap-4 w-full relative z-10">
        {Object.entries(materiData).map(([key, data]) => (
          <button
            key={key}
            onClick={() => { setActiveMateri(key); setCurrentMiniQIndex(0); setScreen('materi'); }}
            className={`${data.color} p-4 rounded-3xl shadow-lg border-4 border-white transform transition-all hover:-translate-y-1 active:scale-95 text-left flex items-center justify-between group`}
          >
            <div className="flex items-center gap-3">
              <div className="text-3xl bg-white/30 p-2 rounded-2xl">{data.icon}</div>
              <div>
                <h3 className="text-lg font-bold text-white shadow-sm">{data.title}</h3>
                <p className="text-white/90 font-medium mt-1 text-sm flex items-center gap-1">
                  Pelajari <ArrowRight size={14} />
                </p>
              </div>
            </div>
            {materiProgress[key] && (
              <div className="bg-yellow-300 rounded-full p-1 border-2 border-yellow-500 shadow-md">
                <Star className="text-yellow-600 fill-current" size={20} />
              </div>
            )}
          </button>
        ))}
      </div>

      <div className="mt-6 text-center relative z-10 pb-4">
        <div className="bg-white/90 p-5 rounded-3xl w-full shadow-lg border-4 border-dashed border-gray-300 flex flex-col items-center">
          <Award size={40} className="text-yellow-500 mb-2" />
          <h3 className="text-lg font-bold text-gray-800 mb-1">Tantangan Akhir</h3>
          <p className="text-gray-600 mb-4 text-sm font-medium">Uji pengetahuanmu di kuis akhir!</p>
          <button
            onClick={() => { resetQuiz(); }}
            className="bg-purple-500 hover:bg-purple-600 text-white font-bold text-base px-6 py-3 rounded-full shadow-xl active:scale-95 flex items-center justify-center gap-2 w-full"
          >
            <Map size={18} /> Kuis Akhir
          </button>
        </div>
      </div>
      
      {/* Decorative background elements */}
      <div className="absolute top-10 left-2 text-4xl opacity-30 pointer-events-none">☁️</div>
      <div className="absolute top-40 right-2 text-4xl opacity-30 pointer-events-none">☁️</div>
      <div className="absolute bottom-10 left-4 text-4xl opacity-30 pointer-events-none">🌲</div>
    </div>
  );

  const renderMateri = () => {
    const data = materiData[activeMateri];
    return (
      <div className="flex-1 flex flex-col bg-gray-50 pb-6">
        <div className="p-4 pb-0">
          <button 
            onClick={() => setScreen('map')}
            className="flex items-center gap-1 bg-white text-gray-700 px-3 py-1.5 rounded-xl font-bold shadow-sm border-2 border-gray-200 active:bg-gray-100 mb-4 text-sm"
          >
            ← Kembali
          </button>
        </div>

        <div className={`${data.color} p-6 text-center text-white shadow-md relative overflow-hidden mx-4 rounded-3xl mb-4`}>
          <div className="absolute -top-6 -right-6 text-7xl opacity-20">{data.icon}</div>
          <h2 className="text-2xl font-black mb-2 relative z-10">{data.title}</h2>
          <div className="text-5xl mt-2 relative z-10">{data.icon}</div>
        </div>

        <div className="bg-white rounded-3xl shadow-md p-5 border-x-2 border-b-4 border-gray-100 text-gray-800 mx-4 flex flex-col gap-6">
          <section>
            <h3 className="text-lg font-bold text-blue-600 flex items-center gap-2 mb-2">
              <BookOpen size={18} /> Pengertian
            </h3>
            <p className="text-sm leading-relaxed bg-blue-50 p-3 rounded-xl border-l-4 border-blue-400">
              {data.pengertian}
            </p>
          </section>

          <section>
            <h3 className="text-lg font-bold text-purple-600 mb-2">Ciri-ciri:</h3>
            <ul className="space-y-2">
              {data.ciri.map((c, i) => (
                <li key={i} className="flex items-start gap-2 text-sm bg-purple-50 p-2.5 rounded-lg">
                  <CheckCircle className="text-purple-500 shrink-0 mt-0.5" size={16} />
                  <span>{c}</span>
                </li>
              ))}
            </ul>
          </section>

          <section>
            <h3 className="text-lg font-bold text-green-600 mb-3">Contoh Kalimat:</h3>
            <div className="flex flex-col gap-3">
              {data.contoh.map((c, i) => (
                <div key={i} className="bg-green-50 border-2 border-green-200 p-3 rounded-2xl flex flex-row items-center gap-4 text-left shadow-sm">
                  <div className="text-3xl shrink-0">{c.img}</div>
                  <p className="font-semibold text-sm">"{c.text}"</p>
                </div>
              ))}
            </div>
          </section>

          {}
          <div className="bg-yellow-100 border-2 border-yellow-300 rounded-3xl p-4 text-center relative mt-2">
            <div className="absolute -top-4 left-1/2 -translate-x-1/2 bg-yellow-400 text-yellow-900 font-black px-4 py-1 rounded-full shadow-md text-xs whitespace-nowrap">
              Misi Bintang! ⭐
            </div>
            <h4 className="text-base font-bold mt-3 mb-4 leading-snug">
              {data.miniQuiz[currentMiniQIndex % data.miniQuiz.length].question}
            </h4>
            <div className="flex flex-col gap-3">
              {data.miniQuiz[currentMiniQIndex % data.miniQuiz.length].options.map((opt, idx) => (
                <button
                  key={idx}
                  onClick={() => handleMiniQuiz(activeMateri, idx)}
                  className="bg-white border-2 border-gray-200 active:border-yellow-400 text-sm font-semibold p-3 rounded-xl shadow-sm text-left flex justify-between items-center group"
                >
                  <span className="flex-1 pr-2">{String.fromCharCode(65 + idx)}. {opt}</span>
                  <div className="w-5 h-5 shrink-0 rounded-full border-2 border-gray-300 group-active:border-yellow-500"></div>
                </button>
              ))}
            </div>
          </div>
        </div>
      </div>
    );
  };

  const renderQuiz = () => {
    const question = finalQuizData[currentQIndex];
    const progress = ((currentQIndex) / finalQuizData.length) * 100;

    return (
      <div className="flex-1 flex flex-col p-4 bg-purple-50 items-center justify-center relative overflow-hidden">
        {/* Progress bar */}
        <div className="w-full mb-6 relative z-10">
          <div className="flex justify-between font-bold text-purple-800 mb-1 text-sm">
            <span>Soal {currentQIndex + 1}/{finalQuizData.length}</span>
            <span>{Math.round(progress)}%</span>
          </div>
          <div className="w-full bg-purple-200 rounded-full h-3 shadow-inner">
            <div 
              className="bg-purple-600 h-3 rounded-full transition-all duration-500 ease-out" 
              style={{ width: `${progress}%` }}
            ></div>
          </div>
        </div>

        <div className="bg-white p-5 rounded-3xl shadow-xl w-full border-t-4 border-purple-500 text-center relative z-10 flex-1 flex flex-col">
           <div className="text-4xl mb-2 mx-auto bg-white rounded-full p-2 shadow-sm border-2 border-purple-200 w-max -mt-10">
             🤔
           </div>
          <h2 className="text-lg sm:text-xl font-bold text-gray-800 mt-2 mb-6 leading-relaxed flex-1 flex items-center justify-center">
            {question.q}
          </h2>

          <div className="flex flex-col gap-3 mb-2">
            {question.o.map((opt, idx) => (
              <button
                key={idx}
                onClick={() => handleQuizAnswer(idx)}
                className="bg-gray-50 border-2 border-purple-100 active:border-purple-400 active:bg-purple-100 text-sm font-bold text-gray-700 p-3 rounded-2xl shadow-sm transition-all text-left flex items-center"
              >
                <span className="bg-purple-200 text-purple-800 w-8 h-8 flex items-center justify-center rounded-full mr-3 shrink-0 shadow-inner">
                  {String.fromCharCode(65 + idx)}
                </span>
                {opt}
              </button>
            ))}
          </div>
        </div>
      </div>
    );
  };

  const FeedbackOverlay = () => {
    if (!showFeedback || !feedbackData) return null;
    const isCorrect = feedbackData.isCorrect;

    return (
      <div className="absolute inset-0 bg-black/60 backdrop-blur-sm z-50 flex items-center justify-center p-4">
        <div className="bg-white rounded-3xl p-6 w-full text-center shadow-2xl animate-bounce-short">
          <div className={`inline-flex rounded-full p-3 mb-3 ${isCorrect ? 'bg-green-100 text-green-600' : 'bg-red-100 text-red-600'}`}>
            {isCorrect ? <CheckCircle size={60} /> : <XCircle size={60} />}
          </div>
          <h2 className={`text-2xl font-black mb-3 ${isCorrect ? 'text-green-600' : 'text-red-600'}`}>
            {isCorrect ? 'BENAR! 🎉' : 'KURANG TEPAT! 😅'}
          </h2>
          <div className="bg-gray-100 p-3 rounded-xl text-sm font-medium text-gray-700 mb-6 border-l-4 border-blue-400 text-left">
            <span className="font-bold block mb-1">Pembahasan:</span>
            {feedbackData.text}
          </div>
          <button
            onClick={() => {
              if (screen === 'materi') {
                setShowFeedback(false);
                if (feedbackData.isCorrect) {
                  setScreen('map');
                  setCurrentMiniQIndex(0);
                } else {
                  setCurrentMiniQIndex((prev) => prev + 1);
                }
              } else {
                nextQuizQuestion();
              }
            }}
            className="w-full bg-blue-500 hover:bg-blue-600 text-white font-bold text-lg py-3 rounded-2xl shadow-lg active:scale-95 flex justify-center items-center gap-2"
          >
            Lanjutkan <ArrowRight size={18} />
          </button>
        </div>
      </div>
    );
  };

  const renderResult = () => {
    const finalScore = Math.round((score / finalQuizData.length) * 100);
    let message = "";
    let colorClass = "";
    let emoji = "";

    if (finalScore >= 90) {
      message = "Luar biasa! Kamu hebat!";
      colorClass = "text-green-600";
      emoji = "🏆";
    } else if (finalScore >= 75) {
      message = "Bagus! Terus berlatih ya!";
      colorClass = "text-blue-600";
      emoji = "👍";
    } else {
      message = "Jangan menyerah! Coba lagi!";
      colorClass = "text-orange-500";
      emoji = "💪";
    }

    return (
      <div className="flex-1 flex flex-col items-center justify-center p-4 bg-gradient-to-br from-yellow-100 via-yellow-50 to-orange-100 overflow-y-auto">
        <div className="bg-white p-6 rounded-3xl shadow-2xl w-full text-center border-4 border-yellow-300 relative mt-10">
          <div className="absolute -top-12 left-1/2 -translate-x-1/2 text-6xl drop-shadow-xl animate-bounce">
            {emoji}
          </div>
          
          <h2 className="text-2xl font-black text-gray-800 mt-6 mb-1">HASIL AKHIR</h2>
          <p className="text-sm font-bold text-gray-500 mb-6">Kuis Kota Majas</p>

          <div className="flex justify-center items-center mb-6">
            <div className="bg-gray-50 rounded-full w-32 h-32 flex flex-col items-center justify-center shadow-inner border-4 border-gray-200">
              <span className="text-4xl font-black text-blue-600">{finalScore}</span>
              <span className="text-sm font-bold text-gray-400">/ 100</span>
            </div>
          </div>

          <div className="grid grid-cols-2 gap-3 mb-6">
            <div className="bg-green-100 p-3 rounded-2xl border-2 border-green-200">
              <p className="text-green-800 font-bold text-sm">Benar</p>
              <p className="text-2xl font-black text-green-600">{quizAnswers.correct}</p>
            </div>
            <div className="bg-red-100 p-3 rounded-2xl border-2 border-red-200">
              <p className="text-red-800 font-bold text-sm">Salah</p>
              <p className="text-2xl font-black text-red-600">{quizAnswers.wrong}</p>
            </div>
          </div>

          <p className={`text-lg font-bold ${colorClass} mb-6 p-3 bg-gray-50 rounded-xl`}>
            "{message}"
          </p>

          <div className="flex flex-col gap-3">
            <button 
              onClick={() => { resetQuiz(); }}
              className="w-full bg-yellow-400 hover:bg-yellow-500 text-yellow-900 font-bold text-base py-3 rounded-full shadow-md active:scale-95 flex items-center justify-center gap-2"
            >
              <RefreshCw size={18} /> Ulangi Kuis
            </button>
            <button 
              onClick={() => setScreen('map')}
              className="w-full bg-blue-500 hover:bg-blue-600 text-white font-bold text-base py-3 rounded-full shadow-md active:scale-95 flex items-center justify-center gap-2"
            >
              <BookOpen size={18} /> Pelajari Lagi
            </button>
          </div>
        </div>
      </div>
    );
  };

  return (
    <div className="min-h-screen bg-gray-900 sm:py-6 sm:px-4 font-sans flex flex-col items-center justify-center selection:bg-yellow-300 selection:text-black">
      <style dangerouslySetInnerHTML={{__html: `
        @keyframes bounce-slow {
          0%, 100% { transform: translateY(-5%) rotate(2deg); }
          50% { transform: translateY(0) rotate(0deg); }
        }
        .animate-bounce-slow {
          animation: bounce-slow 3s ease-in-out infinite;
        }
        @keyframes bounce-short {
          0% { transform: scale(0.9); opacity: 0; }
          50% { transform: scale(1.05); opacity: 1; }
          100% { transform: scale(1); opacity: 1; }
        }
        .animate-bounce-short {
          animation: bounce-short 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards;
        }
        /* Custom scrollbar for webkit */
        ::-webkit-scrollbar { width: 6px; }
        ::-webkit-scrollbar-track { background: transparent; }
        ::-webkit-scrollbar-thumb { background: rgba(0,0,0,0.2); border-radius: 10px; }
      `}} />

      {/* Mobile Device Mockup Container - 9:16 Aspect Ratio */}
      <div className="w-full h-[100dvh] sm:h-auto sm:max-h-[850px] sm:w-[400px] sm:aspect-[9/16] bg-white sm:rounded-[2.5rem] shadow-2xl overflow-hidden flex flex-col relative sm:border-[12px] border-gray-800">
        
        {screen !== 'home' && <TopNav />}

        <main className="flex-1 overflow-y-auto overflow-x-hidden flex flex-col bg-sky-100 relative">
          {screen === 'home' && renderHome()}
          {screen === 'map' && renderMap()}
          {screen === 'materi' && renderMateri()}
          {screen === 'quiz' && renderQuiz()}
          {screen === 'result' && renderResult()}
        </main>
        
        <FeedbackOverlay />

      </div>
    </div>
  );
}
