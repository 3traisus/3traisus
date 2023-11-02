<html>

<head>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.5.1/gsap.min.js"></script>
    <style>
        .circle {
            display: inline-block;
            border-radius: 50%;
            width: 100px;
            height: 100px;
        }

        .circle:nth-of-type(1) {
            background: blue;
        }

        .circle:nth-of-type(2) {
            background: red;
        }

        .circle:nth-of-type(3) {
            background: orange;
        }

        .circle:nth-of-type(4) {
            background: green;
        }
    </style>
</head>

<body>
    <img id="logo" src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/16327/logo-man.svg" />
    <!-- <span class="circle"></span>
    <span class="circle"></span>
    <span class="circle"></span>
    <span class="circle"></span>
    <button class="play">play</button>
    <button class="pause">pause</button>
    <button class="reverse">reverse</button>
    <button class="slow">slow</button> -->
    <script>

        // SET

        // gsap.set('#logo', {
        //     backgroundColor: 'red',
        // });

        // TO

        // gsap.to('#logo', {
        //     duration: 2,
        //     x: 300,
        //     backgroundColor: 'green',
        //     borderRadius: '20%',
        //     border: '5px solid blue',
        //     ease: 'linear'
        // });

        // OBJECT

        // let object = { value: 100 };
        // gsap.to(object, {
        //     duration: 2,
        //     value: 1000,
        //     onStart: () => { console.log('start', object.value); },
        //     onUpdate: () => { console.log(object.value) },
        //     onComplete: () => { console.log('end', object.value); }
        // });

        // FROM

        // gsap.from('#logo', {
        //     duration: 2,
        //     backgroundColor: 'pink',
        //     opacity: 0
        // });

        // STAGGER

        // let tween = gsap.from('.circle', {
        //     duration: .3,
        //     y: -200, //'random(-500,500)',
        //     scale: 0,
        //     stagger: 0.5,
        //     delay: 2 // it's better to use timeline
        // });

        // CONTROLS

        // document.querySelector('.play').onclick = () => tween.play();
        // document.querySelector('.pause').onclick = () => tween.pause();
        // document.querySelector('.reverse').onclick = () => tween.reverse();
        // document.querySelector('.slow').onclick = () => tween.timeScale(.2);

        // TIMELINE 

        // let tl = gsap.timeline({ repeat: 1, yoyo: true });
        // tl.from('#logo', {
        //     duration: 2,
        //     rotate: 360
        // });

        // LABEL 

        //tl.addLabel('label1', "+=1");

        // tl.from('.circle', {
        //     duration: .2,
        //     scale: 0,
        //     stagger: .5
        // }, '+=1');

        // REPEAT (-1 infinite | yoyo)


    </script>
</body>

</html>

