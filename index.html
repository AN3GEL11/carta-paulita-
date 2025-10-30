<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> para Paulita</title>
    <script crossorigin src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
    <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        * {
            -webkit-tap-highlight-color: transparent;
        }
        @keyframes fall {
            to {
                transform: translateY(100vh) rotate(360deg);
                opacity: 0;
            }
        }
        @keyframes float {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(10deg); }
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: scale(0.9);
            }
            to {
                opacity: 1;
                transform: scale(1);
            }
        }
        .animate-fadeIn {
            animation: fadeIn 0.5s ease-out;
        }
    </style>
</head>
<body>
    <div id="root"></div>

    <script type="text/babel">
        const { useState } = React;

        // Iconos simplificados
        const Heart = ({ className, size = 24, fill }) => (
            <svg className={className} width={size} height={size} viewBox="0 0 24 24" fill={fill || "none"} stroke="currentColor" strokeWidth="2">
                <path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"></path>
            </svg>
        );

        const Sparkles = ({ className, size = 24, fill }) => (
            <svg className={className} width={size} height={size} viewBox="0 0 24 24" fill={fill || "none"} stroke="currentColor" strokeWidth="2">
                <path d="M12 3v18m9-9H3m15.364 6.364L5.636 5.636m12.728 0L5.636 18.364"></path>
            </svg>
        );

        const Gift = ({ className, size = 24, fill }) => (
            <svg className={className} width={size} height={size} viewBox="0 0 24 24" fill={fill || "none"} stroke="currentColor" strokeWidth="2">
                <polyline points="20 12 20 22 4 22 4 12"></polyline>
                <rect x="2" y="7" width="20" height="5"></rect>
                <line x1="12" y1="22" x2="12" y2="7"></line>
                <path d="M12 7H7.5a2.5 2.5 0 0 1 0-5C11 2 12 7 12 7z"></path>
                <path d="M12 7h4.5a2.5 2.5 0 0 0 0-5C13 2 12 7 12 7z"></path>
            </svg>
        );

        const Cake = ({ className, size = 24, fill }) => (
            <svg className={className} width={size} height={size} viewBox="0 0 24 24" fill={fill || "none"} stroke="currentColor" strokeWidth="2">
                <path d="M20 21v-8a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2v8"></path>
                <path d="M4 16s.5-1 2-1 2.5 2 4 2 2.5-2 4-2 2.5 2 4 2 2-1 2-1"></path>
                <path d="M2 21h20"></path>
                <path d="M7 8v3"></path>
                <path d="M12 8v3"></path>
                <path d="M17 8v3"></path>
                <path d="M7 4h.01"></path>
                <path d="M12 4h.01"></path>
                <path d="M17 4h.01"></path>
            </svg>
        );

        function BirthdayCard() {
            const [isOpen, setIsOpen] = useState(false);
            const [showConfetti, setShowConfetti] = useState(false);

            const handleOpen = () => {
                setIsOpen(true);
                setShowConfetti(true);
                setTimeout(() => setShowConfetti(false), 3000);
            };

            const handleClose = () => {
                setIsOpen(false);
            };

            return (
                <div className="min-h-screen bg-gradient-to-br from-pink-200 via-purple-200 to-blue-200 flex items-center justify-center p-4 overflow-hidden">
                    
                    {/* Confetti */}
                    {showConfetti && (
                        <div className="fixed inset-0 pointer-events-none z-50">
                            {[...Array(50)].map((_, i) => (
                                <div
                                    key={i}
                                    className="absolute animate-bounce"
                                    style={{
                                        left: `${Math.random() * 100}%`,
                                        top: '-20px',
                                        animation: `fall ${Math.random() * 3 + 2}s linear`,
                                        animationDelay: `${Math.random() * 0.5}s`,
                                        fontSize: '24px'
                                    }}
                                >
                                    {['🎉', '🎊', '✨', '💖', '🌷', '🎈'][Math.floor(Math.random() * 6)]}
                                </div>
                            ))}
                        </div>
                    )}

                    {!isOpen ? (
                        // Sobre cerrado con botón
                        <div className="text-center space-y-6">
                            <div className="relative">
                                {/* Sobre */}
                                <div className="relative w-80 h-56 bg-gradient-to-br from-pink-400 to-purple-400 rounded-lg shadow-2xl mx-auto">
                                    {/* Decoración del sobre */}
                                    <div className="absolute inset-0 flex items-center justify-center">
                                        <div className="text-center space-y-2">
                                            <div className="flex justify-center gap-2">
                                                <Heart className="text-white animate-pulse" size={32} fill="white" />
                                                <Sparkles className="text-yellow-300 animate-pulse" size={32} fill="#fde047" />
                                            </div>
                                            <p className="text-white font-bold text-2xl">Para: Paulita</p>
                                        </div>
                                    </div>
                                    
                                    {/* Solapa del sobre */}
                                    <div className="absolute top-0 left-0 right-0 h-28 bg-gradient-to-br from-pink-500 to-purple-500 origin-top transform-gpu"
                                        style={{
                                            clipPath: 'polygon(0 0, 50% 100%, 100% 0)',
                                        }}>
                                    </div>

                                    {/* Sello */}
                                    <div className="absolute top-4 right-4 w-12 h-12 bg-white rounded-full flex items-center justify-center border-2 border-pink-300">
                                        <span className="text-2xl">🌷</span>
                                    </div>
                                </div>

                                {/* Flores decorativas alrededor */}
                                <div className="absolute -top-6 -left-6 text-4xl animate-bounce pointer-events-none">🌷</div>
                                <div className="absolute -top-6 -right-6 text-4xl animate-bounce pointer-events-none" style={{animationDelay: '0.3s'}}>🌸</div>
                                <div className="absolute -bottom-6 -left-6 text-4xl animate-bounce pointer-events-none" style={{animationDelay: '0.6s'}}>🌺</div>
                                <div className="absolute -bottom-6 -right-6 text-4xl animate-bounce pointer-events-none" style={{animationDelay: '0.9s'}}>💐</div>
                            </div>

                            {/* Botón grande para abrir */}
                            <button
                                onClick={handleOpen}
                                className="bg-gradient-to-r from-pink-500 to-purple-500 text-white px-10 py-5 rounded-full text-xl md:text-2xl font-bold shadow-2xl hover:shadow-3xl transform hover:scale-105 active:scale-95 transition-all animate-pulse"
                                style={{ touchAction: 'manipulation' }}
                            >
                                💌 Abrir Carta 💌
                            </button>

                            <p className="text-purple-600 font-semibold text-lg animate-bounce">
                                ⬆️ Presiona el botón ⬆️
                            </p>
                        </div>
                    ) : (
                        // Carta abierta
                        <div className="w-full max-w-2xl animate-fadeIn">
                            <div className="bg-white rounded-3xl shadow-2xl overflow-hidden">
                                {/* Encabezado decorativo */}
                                <div className="bg-gradient-to-r from-pink-400 via-purple-400 to-pink-400 p-6 relative overflow-hidden">
                                    <div className="absolute inset-0 opacity-20">
                                        {[...Array(20)].map((_, i) => (
                                            <div
                                                key={i}
                                                className="absolute text-white text-2xl pointer-events-none"
                                                style={{
                                                    left: `${Math.random() * 100}%`,
                                                    top: `${Math.random() * 100}%`,
                                                    animation: `float ${Math.random() * 3 + 2}s ease-in-out infinite`,
                                                    animationDelay: `${Math.random() * 2}s`
                                                }}
                                            >
                                                {['✨', '💖', '🌷'][Math.floor(Math.random() * 3)]}
                                            </div>
                                        ))}
                                    </div>
                                    
                                    <div className="relative text-center space-y-2">
                                        <div className="flex justify-center gap-3 mb-3">
                                            <Cake className="text-white" size={40} fill="white" />
                                            <Gift className="text-white" size={40} fill="white" />
                                            <Cake className="text-white" size={40} fill="white" />
                                        </div>
                                        <h1 className="text-4xl md:text-5xl font-bold text-white drop-shadow-lg">
                                            ¡Felices 15 Años!
                                        </h1>
                                        <h2 className="text-3xl md:text-4xl font-bold text-yellow-200 drop-shadow-lg">
                                            Paulita
                                        </h2>
                                        <div className="flex justify-center gap-2 mt-3">
                                            <Heart className="text-yellow-200 animate-pulse" size={24} fill="#fef08a" />
                                            <Sparkles className="text-yellow-300 animate-pulse" size={24} fill="#fde047" />
                                            <Heart className="text-yellow-200 animate-pulse" size={24} fill="#fef08a" />
                                        </div>
                                    </div>
                                </div>

                                {/* Contenido de la carta */}
                                <div className="p-6 md:p-8 space-y-6 bg-gradient-to-b from-pink-50 to-purple-50">
                                    <div className="text-base md:text-lg leading-relaxed text-gray-700 space-y-4" style={{ fontFamily: 'Georgia, serif' }}>
                                        <p className="text-xl md:text-2xl font-semibold text-pink-600 text-center mb-6">
                                            Querida Paulita, 💖
                                        </p>
                                        
                                        <p>
                                            Hoy te quiero felicitar por tu cumpleaños y más por tus <span className="font-bold text-purple-600">15 años</span>. 
                                            Me acuerdo la vez que me dijiste que te gustaban los tulipanes... aunque no te puedo dar unos reales, 
                                            te regalo esta carta con muchos tulipanes regados en ella. 🌷
                                        </p>
                                        
                                        <div className="bg-white rounded-xl p-4 md:p-6 shadow-md border-2 border-pink-200 my-6 relative overflow-hidden">
                                            {/* Tulipanes decorativos alrededor del mensaje */}
                                            <div className="absolute top-2 left-2 text-xl md:text-2xl opacity-30">🌷</div>
                                            <div className="absolute top-2 right-2 text-xl md:text-2xl opacity-30">🌷</div>
                                            <div className="absolute bottom-2 left-2 text-xl md:text-2xl opacity-30">🌷</div>
                                            <div className="absolute bottom-2 right-2 text-xl md:text-2xl opacity-30">🌷</div>
                                            
                                            <p className="text-lg md:text-xl text-center font-semibold text-purple-600 relative z-10">
                                                Que cada tulipán te recuerde lo <span className="text-pink-600">bonita</span>, 
                                                <span className="text-purple-600"> única</span>, 
                                                <span className="text-pink-600"> extraordinaria</span>, 
                                                <span className="text-purple-600"> inteligente</span> y la 
                                                <span className="text-pink-600"> increíble persona</span> que eres.
                                            </p>
                                        </div>
                                        
                                        <p>
                                            Que este nuevo capítulo de tu vida esté lleno de aventuras maravillosas, 
                                            de sueños cumplidos y de momentos que te hagan sonreír cada vez que los recuerdes.
                                        </p>
                                        
                                        <p>
                                            Que sigas brillando con esa luz especial que te caracteriza, 
                                            que tu camino esté lleno de colores como los tulipanes que tanto te gustan, 
                                            y que cada día sea una nueva oportunidad para ser feliz.
                                        </p>
                                        
                                        <p className="text-lg md:text-xl font-bold text-center text-pink-600 mt-6">
                                            Solo me queda desearte un muy feliz cumpleaños. 🎂✨
                                        </p>
                                        
                                        <div className="text-center space-y-2 mt-6 pt-6 border-t-2 border-pink-200">
                                            <p className="text-gray-600">Con todo mi cariño,</p>
                                            <p className="text-2xl font-bold text-purple-600" style={{ fontFamily: 'Brush Script MT, cursive' }}>
                                                ❤️
                                            </p>
                                        </div>
                                    </div>

                                    {/* Jardín de tulipanes en la parte inferior */}
                                    <div className="flex justify-center gap-2 text-2xl md:text-3xl pt-4 flex-wrap">
                                        <span className="animate-bounce">🌷</span>
                                        <span className="animate-bounce" style={{animationDelay: '0.1s'}}>🌷</span>
                                        <span className="animate-bounce" style={{animationDelay: '0.2s'}}>🌸</span>
                                        <span className="animate-bounce" style={{animationDelay: '0.3s'}}>🌷</span>
                                        <span className="animate-bounce" style={{animationDelay: '0.4s'}}>🌺</span>
                                        <span className="animate-bounce" style={{animationDelay: '0.5s'}}>🌷</span>
                                        <span className="animate-bounce" style={{animationDelay: '0.6s'}}>💐</span>
                                        <span className="animate-bounce" style={{animationDelay: '0.7s'}}>🌷</span>
                                        <span className="animate-bounce" style={{animationDelay: '0.8s'}}>🌸</span>
                                        <span className="animate-bounce" style={{animationDelay: '0.9s'}}>🌷</span>
                                    </div>
                                </div>

                                {/* Botón para cerrar */}
                                <div className="bg-gradient-to-r from-pink-400 to-purple-400 p-4 text-center">
                                    <button
                                        onClick={handleClose}
                                        className="bg-white text-purple-600 px-8 py-4 rounded-full text-lg font-bold shadow-lg hover:shadow-xl active:scale-95 transition-all"
                                        style={{ touchAction: 'manipulation' }}
                                    >
                                        💌 Cerrar carta
                                    </button>
                                </div>
                            </div>
                        </div>
                    )}
                </div>
            );
        }

        ReactDOM.render(<BirthdayCard />, document.getElementById('root'));
    </script>
</body>
</html>
