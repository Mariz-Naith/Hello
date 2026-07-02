<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>THE ESTATE • Legacy & Honour</title>
  
    <!-- Anime.js -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/3.2.1/anime.min.js"></script>
    <!-- Three.js -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r134/three.min.js"></script>

    <style>
        :root {
            --gold: #c9a96e;
        }
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Crimson Text', serif;
            color: #f5f0e6;
            line-height: 1.8;
            background: #0a1814;
            overflow-x: hidden;
        }
        .page-frame {
            max-width: 1280px;
            margin: 20px auto;
            border: 14px solid var(--gold);
            box-shadow: 0 0 80px rgba(201, 169, 110, 0.45);
            overflow: hidden;
        }
        /* NAV */
        nav {
            position: fixed;
            top: 0; width: 100%;
            background: rgba(15, 44, 31, 0.96);
            backdrop-filter: blur(16px);
            z-index: 1000;
            border-bottom: 3px solid var(--gold);
        }
        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 1.4rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            font-family: 'Playfair Display', serif;
            font-size: 2.2rem;
            color: var(--gold);
            letter-spacing: 4px;
        }
        .nav-links a {
            color: #f5f0e6;
            text-decoration: none;
            margin-left: 2.4rem;
            font-size: 1.08rem;
            position: relative;
        }
        .nav-links a::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -6px;
            left: 0;
            background: var(--gold);
            transition: width 0.4s;
        }
        .nav-links a:hover::after { width: 100%; }

        /* HERO with 3D */
        #hero {
            height: 100vh;
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            overflow: hidden;
        }
        #three-container {
            position: absolute;
            top: 0; left: 0;
            width: 100%; height: 100%;
            z-index: 1;
        }
        .hero-content {
            z-index: 2;
            max-width: 900px;
        }
        .crest {
            font-family: 'Playfair Display', serif;
            font-size: 7.8rem;
            font-weight: 700;
            color: var(--gold);
            letter-spacing: 20px;
            text-shadow: 0 15px 50px rgba(0,0,0,0.9);
        }
        .tagline {
            font-size: 2.1rem;
            letter-spacing: 12px;
            color: #e8d9b8;
            font-style: italic;
            margin: 1.5rem 0 2.5rem;
        }
        .cta-button {
            background: transparent;
            color: var(--gold);
            border: 3px solid var(--gold);
            padding: 1rem 3rem;
            font-size: 1.1rem;
            letter-spacing: 4px;
            cursor: pointer;
            transition: all 0.4s;
        }
        .cta-button:hover {
            background: var(--gold);
            color: #0f2c1f;
        }

        /* SECTIONS */
        .section {
            padding: 7rem 2rem;
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            position: relative;
        }
        .section::before {
            content: '';
            position: absolute;
            inset: 0;
            background: rgba(15, 44, 31, 0.78);
            z-index: 1;
        }
        .section-content {
            position: relative;
            z-index: 2;
            max-width: 1100px;
            margin: 0 auto;
        }
        h2 {
            font-family: 'Playfair Display', serif;
            color: var(--gold);
            font-size: 3.4rem;
            border-bottom: 5px solid var(--gold);
            padding-bottom: 1.2rem;
            display: inline-block;
            margin-bottom: 2rem;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(360px, 1fr));
            gap: 2.8rem;
        }

        /* CARD WITH SLIDING SHINE */
        .card {
            background: rgba(30, 45, 38, 0.95);
            border: 4px solid var(--gold);
            border-radius: 16px;
            padding: 2rem;
            cursor: pointer;
            transition: all 0.5s cubic-bezier(0.23, 1, 0.32, 1);
            position: relative;
            overflow: hidden;
        }
        .card::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 40%;
            height: 200%;
            background: linear-gradient(
                120deg,
                transparent,
                rgba(255, 255, 255, 0.35),
                transparent
            );
            transform: skewX(-25deg);
            transition: left 0.7s ease;
            opacity: 0;
            z-index: 1;
        }
        .card:hover::before {
            left: 120%;
            opacity: 1;
            transition: left 0.8s ease;
        }
        .card:hover {
            transform: translateY(-25px) scale(1.04);
            box-shadow: 0 30px 70px rgba(201, 169, 110, 0.45);
        }
        .card img {
            width: 100%;
            height: 240px;
            object-fit: cover;
            border-radius: 12px;
            margin-bottom: 1.4rem;
            border: 3px solid var(--gold);
            position: relative;
            z-index: 2;
        }
        .card h3, .card p {
            position: relative;
            z-index: 2;
        }

        .divider {
            height: 90px;
            background: linear-gradient(to right, transparent, var(--gold), transparent);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2.8rem;
            color: var(--gold);
        }

        /* Modal */
        .modal {
            display: none;
            position: fixed;
            inset: 0;
            background: rgba(10, 20, 18, 0.98);
            z-index: 2000;
            align-items: center;
            justify-content: center;
        }
        .modal-content {
            background: #1a2f24;
            border: 10px double var(--gold);
            max-width: 860px;
            width: 94%;
            padding: 3.5rem;
            border-radius: 18px;
            position: relative;
            max-height: 90vh;
            overflow-y: auto;
        }
        .close {
            position: absolute;
            top: 20px;
            right: 30px;
            font-size: 3rem;
            color: var(--gold);
            cursor: pointer;
        }
        .wiki-style p {
            margin-bottom: 1.3rem;
            text-align: justify;
        }
        .wiki-style strong {
            color: var(--gold);
        }

        footer {
            background: #0a1814;
            text-align: center;
            padding: 5rem 2rem;
            border-top: 10px solid var(--gold);
        }
        .footer-title {
            font-family: 'Playfair Display', serif;
            font-size: 3rem;
            color: var(--gold);
        }
    </style>
</head>
<body>
    <div class="page-frame">
        <nav>
            <div class="nav-container">
                <div class="logo">THE ESTATE</div>
                <div class="nav-links">
                    <a href="#history">Legacy</a>
                    <a href="#machines">Power</a>
                    <a href="#body">Body</a>
                    <a href="#style">Presence</a>
                    <a href="#money">Empire</a>
                </div>
            </div>
        </nav>

        <header id="hero">
            <div id="three-container"></div>
            <div class="hero-content">
                <div class="crest" id="crest">LEGACY</div>
                <p class="tagline" id="tagline">BECOME THE MAN YOU WERE MEANT TO BE</p>
                <button class="cta-button" onclick="document.getElementById('history').scrollIntoView({behavior:'smooth'})">
                    ENTER THE ESTATE
                </button>
            </div>
        </header>

        <section id="history" class="section" style="background-image: url('https://wallpapercave.com/wp/wp16287194.webp');">
            <div class="section-content">
                <h2>Medieval Foundations</h2>
                <div class="grid">
                    <div class="card" onclick="showModal('knights')">
                        <img src="https://wallpapercave.com/wp/wp15388942.png" alt="Knight">
                        <h3>The Knight's Code</h3>
                        <p>Honour. Courage. Discipline.</p>
                    </div>
                    <div class="card" onclick="showModal('castles')">
                        <img src="https://wallpapercave.com/wp/wp4738116.jpg" alt="Castle">
                        <h3>Castles &amp; Strategy</h3>
                        <p>Strong foundations create empires.</p>
                    </div>
                </div>
            </div>
        </section>

        <div class="divider">✦</div>

        <section id="machines" class="section" style="background-image: url('https://wallpapercave.com/wp/BIABia5.jpg');">
            <div class="section-content">
                <h2>Icons of Power</h2>
                <div class="grid">
                    <div class="card" onclick="showModal('ferrari')">
                        <img src="https://wallpapercave.com/wp/wp1985799.jpg" alt="Ferrari">
                        <h3>Ferrari</h3>
                    </div>
                    <div class="card" onclick="showModal('rolls')">
                        <img src="https://wallpapercave.com/wp/wp4904816.jpg" alt="Rolls Royce">
                        <h3>Rolls-Royce</h3>
                    </div>
                    <div class="card" onclick="showModal('mustang')">
                        <img src="https://wallpapercave.com/uwp/uwp4958381.jpeg" alt="Mustang">
                        <h3>Mustang</h3>
                    </div>
                </div>
            </div>
        </section>

        <div class="divider">✦</div>

        <section id="body" class="section" style="background-image: url('https://picsum.photos/id/106/2000/1200');">
            <div class="section-content">
                <h2>Forge Your Body</h2>
                <div class="grid">
                    <div class="card" onclick="showModal('fitness')">
                        <img src="https://picsum.photos/id/103/800/500" alt="Training">
                        <h3>Discipline in Iron</h3>
                        <p>The body is the first empire you must conquer.</p>
                    </div>
                </div>
            </div>
        </section>

        <div class="divider">✦</div>

        <section id="style" class="section" style="background-image: url('https://picsum.photos/id/201/2000/1200');">
            <div class="section-content">
                <h2>Style &amp; Presence</h2>
                <div class="grid">
                    <div class="card" onclick="showModal('watches')">
                        <img src="https://wallpapercave.com/wp/wp16277318.webp" alt="Watch">
                        <h3>Timeless Timepieces</h3>
                    </div>
                    <div class="card" onclick="showModal('grooming')">
                        <img src="https://picsum.photos/id/91/800/500" alt="Grooming">
                        <h3>Grooming &amp; Aura</h3>
                    </div>
                </div>
            </div>
        </section>

        <div class="divider">✦</div>

        <section id="money" class="section" style="background-image: url('https://picsum.photos/id/1016/2000/1200');">
            <div class="section-content">
                <h2>Wealth &amp; Empire</h2>
                <div class="grid">
                    <div class="card" onclick="showModal('money')">
                        <img src="https://wallpapercave.com/wp/wp14867520.jpg" alt="Wealth">
                        <h3>Generational Wealth</h3>
                    </div>
                    <div class="card" onclick="showModal('hustle')">
                        <img src="https://wallpapercave.com/wp/wp11531323.jpg" alt="Hustle">
                        <h3>The Modern Crusade</h3>
                    </div>
                </div>
            </div>
        </section>

        <footer>
            <p class="footer-title">THE ESTATE</p>
            <p>Honour • Discipline • Legacy • Excellence</p>
            <p>Go forth and become the legend you were born to be.</p>
        </footer>
    </div>

    <!-- MODAL -->
    <div id="infoModal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal()">×</span>
            <div id="modalBody" class="wiki-style"></div>
        </div>
    </div>

    <script>
        // 3D Model (kept as requested)
        let scene, camera, renderer, model;
        function init3D() {
            const container = document.getElementById('three-container');
            scene = new THREE.Scene();
            camera = new THREE.PerspectiveCamera(50, window.innerWidth / window.innerHeight, 0.1, 1000);
            renderer = new THREE.WebGLRenderer({ antialias: true, alpha: true });
            renderer.setSize(window.innerWidth, window.innerHeight);
            renderer.setPixelRatio(Math.min(window.devicePixelRatio, 2));
            container.appendChild(renderer.domElement);

            const ambient = new THREE.AmbientLight(0xffffff, 0.7);
            scene.add(ambient);
            const light = new THREE.DirectionalLight(0xc9a96e, 1.5);
            light.position.set(5, 10, 8);
            scene.add(light);

            const geometry = new THREE.SphereGeometry(2.4, 48, 48);
            const material = new THREE.MeshPhongMaterial({
                color: 0xc9a96e,
                shininess: 120,
                specular: 0xffffff,
                metalness: 0.8
            });
            model = new THREE.Mesh(geometry, material);
            scene.add(model);

            camera.position.z = 7;

            let mouseX = 0;
            document.addEventListener('mousemove', (e) => {
                mouseX = (e.clientX / window.innerWidth) * 2 - 1;
            });

            function animate3D() {
                requestAnimationFrame(animate3D);
                if (model) {
                    model.rotation.y = mouseX * 1.2 + Date.now() * 0.0008;
                    model.rotation.x = Math.sin(Date.now() * 0.0015) * 0.15;
                }
                renderer.render(scene, camera);
            }
            animate3D();

            window.addEventListener('resize', () => {
                camera.aspect = window.innerWidth / window.innerHeight;
                camera.updateProjectionMatrix();
                renderer.setSize(window.innerWidth, window.innerHeight);
            });
        }

        function startAnimations() {
            anime({
                targets: '#crest',
                opacity: [0, 1],
                translateY: [-100, 0],
                duration: 1800,
                easing: 'easeOutExpo'
            });
            anime({
                targets: '#tagline',
                opacity: [0, 1],
                translateY: [60, 0],
                duration: 1800,
                delay: 600,
                easing: 'easeOutExpo'
            });
        }

        function animateCards() {
            const cards = document.querySelectorAll('.card');
            const observer = new IntersectionObserver((entries) => {
                entries.forEach((entry, index) => {
                    if (entry.isIntersecting) {
                        anime({
                            targets: entry.target,
                            opacity: [0, 1],
                            translateY: [80, 0],
                            duration: 1000,
                            delay: index * 150,
                            easing: 'easeOutQuad'
                        });
                        observer.unobserve(entry.target);
                    }
                });
            }, { threshold: 0.2 });
            cards.forEach(card => observer.observe(card));
        }

        function showModal(type) {
            const body = document.getElementById('modalBody');
            let content = '';

            if (type === 'knights') {
                content = `
                    <h3 style="color:var(--gold); text-align:center; margin-bottom:1.5rem;">The Knight's Code</h3>
                    <p>A knight was a mounted warrior in medieval Europe who followed a strict code of chivalry. Training typically began at a young age as a page, progressing to squire, and finally being dubbed a knight around the age of 21 in an elaborate ceremony.</p>
                    <p>The ideals of courage, honour, loyalty, and the protection of the weak formed the foundation of knighthood. These virtues transcended the battlefield and shaped the moral character of men who sought greatness.</p>`;
            } else if (type === 'castles') {
                content = `
                    <h3 style="color:var(--gold); text-align:center; margin-bottom:1.5rem;">Castles &amp; Strategy</h3>
                    <p>Medieval castles were fortified structures designed primarily for defence but also served as administrative centres and symbols of noble power. Built with thick stone walls, moats, and strategic positioning, they represented long-term planning and dominance.</p>
                    <p>Many castles stood for centuries, outlasting the individuals who commissioned them, serving as a powerful metaphor for building legacies that endure.</p>`;
            } else if (type === 'ferrari') {
                content = `
                    <h3 style="color:var(--gold); text-align:center; margin-bottom:1.5rem;">Ferrari</h3>
                    <p>Ferrari S.p.A. is an Italian luxury sports car manufacturer founded by Enzo Ferrari in 1939. The company is known for its racing heritage and distinctive red colour, becoming one of the most recognized symbols of performance and exclusivity worldwide.</p>
                    <p>Each Ferrari is handcrafted with meticulous attention to detail, representing the pursuit of engineering excellence and emotional driving experience.</p>`;
            } else if (type === 'rolls') {
                content = `
                    <h3 style="color:var(--gold); text-align:center; margin-bottom:1.5rem;">Rolls-Royce</h3>
                    <p>Rolls-Royce Motor Cars is a British luxury automobile manufacturer founded in 1904. Renowned for exceptional craftsmanship, silent operation, and supreme comfort, Rolls-Royce vehicles are often regarded as the pinnacle of automotive luxury.</p>`;
            } else if (type === 'mustang') {
                content = `
                    <h3 style="color:var(--gold); text-align:center; margin-bottom:1.5rem;">Mustang</h3>
                    <p>The Ford Mustang is an American muscle car introduced in 1964. It became an instant cultural icon, symbolizing freedom, power, and the American spirit. Over 10 million units have been sold since its debut.</p>`;
            } else if (type === 'fitness') {
                content = `
                    <h3 style="color:var(--gold); text-align:center; margin-bottom:1.5rem;">Forge Your Body</h3>
                    <p>Physical training has been a fundamental aspect of masculine development across civilizations. From the Spartans of ancient Greece to the knights of medieval Europe, a strong body was considered essential for both survival and character building.</p>
                    <p>Modern resistance training builds not only muscle mass but also mental resilience, discipline, and self-confidence.</p>`;
            } else if (type === 'watches') {
                content = `
                    <h3 style="color:var(--gold); text-align:center; margin-bottom:1.5rem;">Timeless Timepieces</h3>
                    <p>Luxury watches such as Rolex, Omega, and Patek Philippe represent more than instruments for telling time. They are symbols of precision engineering, personal achievement, and enduring value.</p>`;
            } else if (type === 'grooming') {
                content = `
                    <h3 style="color:var(--gold); text-align:center; margin-bottom:1.5rem;">Grooming &amp; Aura</h3>
                    <p>Personal grooming and presentation have always been important markers of self-respect and social standing. A well-groomed appearance creates strong first impressions and reflects internal discipline.</p>`;
            } else if (type === 'money') {
                content = `
                    <h3 style="color:var(--gold); text-align:center; margin-bottom:1.5rem;">Generational Wealth</h3>
                    <p>Building generational wealth involves converting time and effort into assets that continue to generate value across multiple lifetimes. It requires strategic thinking, patience, and the discipline to delay immediate gratification.</p>`;
            } else if (type === 'hustle') {
                content = `
                    <h3 style="color:var(--gold); text-align:center; margin-bottom:1.5rem;">The Modern Crusade</h3>
                    <p>In today's world, the entrepreneurial hustle represents the drive to identify opportunities, take calculated risks, and build something of lasting value through relentless effort and innovation.</p>`;
            }

            body.innerHTML = content;
            document.getElementById('infoModal').style.display = 'flex';
            
            anime({
                targets: '.modal-content',
                scale: [0.6, 1],
                opacity: [0, 1],
                duration: 600,
                easing: 'easeOutBack'
            });
        }

        function closeModal() {
            anime({
                targets: '.modal-content',
                scale: [1, 0.7],
                opacity: [1, 0],
                duration: 400,
                complete: () => document.getElementById('infoModal').style.display = 'none'
            });
        }

        window.onload = () => {
            init3D();
            startAnimations();
            animateCards();
        };
    </script>
</body>
</html>

