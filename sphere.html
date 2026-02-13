<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>Our Universe</title>
    <style>
        body { margin: 0; overflow: hidden; background: #000; }
        #msg {
            position: absolute; top: 20px; width: 100%; text-align: center;
            color: #ff4d6d; font-family: sans-serif; pointer-events: none;
            text-shadow: 0 0 10px #000; z-index: 10;
        }
    </style>
</head>
<body>
    <div id="msg">
        <h2>You are my universe.</h2>
        <p>Tilt or swipe to explore our stars.</p>
    </div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>

    <script>
        var scene = new THREE.Scene();
        var camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
        var renderer = new THREE.WebGLRenderer({ antialias: true });
        renderer.setSize(window.innerWidth, window.innerHeight);
        document.body.appendChild(renderer.domElement);

        // Create Stars
        var starGeo = new THREE.BufferGeometry();
        var starMat = new THREE.PointsMaterial({ color: 0xffffff, size: 0.8 });
        var starVex = [];
        for (var i = 0; i < 2000; i++) {
            starVex.push((Math.random() - 0.5) * 1500);
            starVex.push((Math.random() - 0.5) * 1500);
            starVex.push((Math.random() - 0.5) * 1500);
        }
        starGeo.setAttribute('position', new THREE.Float32BufferAttribute(starVex, 3));
        var stars = new THREE.Points(starGeo, starMat);
        scene.add(stars);

        // Create the Heart/Core
        var coreGeo = new THREE.SphereGeometry(10, 24, 24);
        var coreMat = new THREE.MeshBasicMaterial({ color: 0xff4d6d });
        var core = new THREE.Mesh(coreGeo, coreMat);
        scene.add(core);

        camera.position.z = 400;

        function animate() {
            requestAnimationFrame(animate);
            stars.rotation.y += 0.001;
            core.rotation.x += 0.01;
            renderer.render(scene, camera);
        }
        animate();

        // Mobile Touch Support
        document.addEventListener('touchmove', function(e) {
            var touch = e.touches[0];
            stars.rotation.x += (touch.pageY - window.innerHeight/2) * 0.00001;
            stars.rotation.y += (touch.pageX - window.innerWidth/2) * 0.00001;
        });

        // Handle Resize
        window.addEventListener('resize', function() {
            camera.aspect = window.innerWidth / window.innerHeight;
            camera.updateProjectionMatrix();
            renderer.setSize(window.innerWidth, window.innerHeight);
        });
    </script>
</body>
</html>
