<template>
    <main>

    
    <header>

        <div class="w-full bg-center bg-cover h-[38rem] bg rounded-3xl	">

            <div class="flex items-center justify-center w-full h-full ">
                <div class="center">
                    <h1>
                        <span>Japan</span>

                        <span>Japan</span>
                        <span>Japan</span>

                    </h1>
                </div>
                <button class="cybr-btn"
                    style="--primary-hue: 0; --primary-shadow-hue: 180; --secondary-shadow-hue: 60;"><span
                        class="cybr-btn__text" data-text="Cool_">Смотреть</span><span
                        class="cybr-btn__glitch"></span></button>
            </div>
        </div>
    </header>
</main>
</template>

<style>
:root {
    --shimmy-distance: 5;
    --primary-hue: 0;
    --primary-lightness: 50;
    --color: #fff;
    --black: #0d0d0d;
    --font-size: 26px;
    --label-size: 9px;
    --shadow-primary-hue: 180;
    --shadow-secondary-hue: 60;
}

main {
  display: flex;
  flex-direction: column;
  transform: rotatex(10deg);
  -webkit-animation: rotateAngle 6s linear infinite;
          animation: rotateAngle 6s linear infinite;
}



@-webkit-keyframes rotateAngle {
  0% {
    transform: rotateY(0deg) rotateX(10deg);
    -webkit-animation-timing-function: cubic-bezier(0.61, 1, 0.88, 1);
            animation-timing-function: cubic-bezier(0.61, 1, 0.88, 1);
  }
  25% {
    transform: rotateY(20deg) rotateX(10deg);
  }
  50% {
    transform: rotateY(0deg) rotateX(10deg);
    -webkit-animation-timing-function: cubic-bezier(0.61, 1, 0.88, 1);
            animation-timing-function: cubic-bezier(0.61, 1, 0.88, 1);
  }
  75% {
    transform: rotateY(-20deg) rotateX(10deg);
  }
  100% {
    transform: rotateY(0deg) rotateX(10deg);
  }
}

@keyframes rotateAngle {
  0% {
    transform: rotateY(0deg) rotateX(10deg);
    -webkit-animation-timing-function: cubic-bezier(0.61, 1, 0.88, 1);
            animation-timing-function: cubic-bezier(0.61, 1, 0.88, 1);
  }
  25% {
    transform: rotateY(20deg) rotateX(10deg);
  }
  50% {
    transform: rotateY(0deg) rotateX(10deg);
    -webkit-animation-timing-function: cubic-bezier(0.61, 1, 0.88, 1);
            animation-timing-function: cubic-bezier(0.61, 1, 0.88, 1);
  }
  75% {
    transform: rotateY(-20deg) rotateX(10deg);
  }
  100% {
    transform: rotateY(0deg) rotateX(10deg);
  }
}
@-webkit-keyframes translateWobble {
  0% {
    opacity: 0;
    transform: translate3d(calc(var(--z) * 0px), calc(var(--z) * 0px), calc(var(--z) * 0px));
  }
  16% {
    transform: translate3d(calc(var(--z) * 160px), calc(var(--z) * 160px), calc(var(--z) * 160px));
  }
  28% {
    opacity: 1;
    transform: translate3d(calc(var(--z) * 70px), calc(var(--z) * 70px), calc(var(--z) * 70px));
  }
  44% {
    transform: translate3d(calc(var(--z) * 130px), calc(var(--z) * 130px), calc(var(--z) * 130px));
  }
  59% {
    transform: translate3d(calc(var(--z) * 85px), calc(var(--z) * 85px), calc(var(--z) * 85px));
  }
  73% {
    transform: translate3d(calc(var(--z) * 110px), calc(var(--z) * 110px), calc(var(--z) * 110px));
  }
  88% {
    opacity: 1;
    transform: translate3d(calc(var(--z) * 90px), calc(var(--z) * 90px), calc(var(--z) * 90px));
  }
  100% {
    opacity: 1;
    transform: translate3d(calc(var(--z) * 100px), calc(var(--z) * 100px), calc(var(--z) * 100px));
  }
}
@keyframes translateWobble {
  0% {
    opacity: 0;
    transform: translate3d(calc(var(--z) * 0px), calc(var(--z) * 0px), calc(var(--z) * 0px));
  }
  16% {
    transform: translate3d(calc(var(--z) * 160px), calc(var(--z) * 160px), calc(var(--z) * 160px));
  }
  28% {
    opacity: 1;
    transform: translate3d(calc(var(--z) * 70px), calc(var(--z) * 70px), calc(var(--z) * 70px));
  }
  44% {
    transform: translate3d(calc(var(--z) * 130px), calc(var(--z) * 130px), calc(var(--z) * 130px));
  }
  59% {
    transform: translate3d(calc(var(--z) * 85px), calc(var(--z) * 85px), calc(var(--z) * 85px));
  }
  73% {
    transform: translate3d(calc(var(--z) * 110px), calc(var(--z) * 110px), calc(var(--z) * 110px));
  }
  88% {
    opacity: 1;
    transform: translate3d(calc(var(--z) * 90px), calc(var(--z) * 90px), calc(var(--z) * 90px));
  }
  100% {
    opacity: 1;
    transform: translate3d(calc(var(--z) * 100px), calc(var(--z) * 100px), calc(var(--z) * 100px));
  }
}
.cybr-btn {
    --primary: hsl(var(--primary-hue), 85%, calc(var(--primary-lightness, 50) * 1%));
    --shadow-primary: hsl(var(--shadow-primary-hue), 90%, 50%);
    --shadow-primary-alpha: hsla(var(--shadow-primary-hue), 90%, 50%, 0.5);
    --shadow-secondary: hsl(var(--shadow-secondary-hue), 90%, 60%);
    font-family: 'Cyber', sans-serif;
    position: relative;
    text-transform: uppercase;
    background: var(--primary);
    font-size: var(--font-size);
    outline: transparent;
    border: 0;
    min-width: 100px;
    -webkit-clip-path: polygon(-10% -10%, 110% -10%, 110% 110%, 10% 110%, -10% 40%);
    clip-path: polygon(-10% -10%, 110% -10%, 110% 110%, 10% 110%, -10% 40%);
    padding: 32px 64px;
    margin-top: 10em;
    box-shadow: -2px 0 1px 0px inset var(--shadow-primary);
    transition: background 0.1s ease;
}

.cybr-btn *,
.cybr-btn *:after {
    outline: transparent;
}

.cybr-btn:hover .cybr-btn__text:after,
.cybr-btn:hover .cybr-btn__glitch:after {
    display: block;
}

.cybr-btn:hover {
    --primary-lightness: 40;
}

.cybr-btn:active {
    --primary-lightness: 30;
}

.cybr-btn__glitch {
    height: 50%;
    width: 50%;
    display: block;
    position: absolute;
    top: 0;
    left: 0;
    filter: drop-shadow(-2px 2px var(--shadow-primary)) drop-shadow(-1px -1px var(--shadow-primary-alpha)) drop-shadow(2px 2px var(--shadow-primary));
}

.cybr-btn__glitch:after {
    display: none;
    background: var(--primary);
    -webkit-animation: shimmy-text 2s infinite alternate ease-in-out;
    animation: shimmy-text 2s infinite alternate ease-in-out;
    content: '';
    height: 98%;
    width: 98%;
    position: absolute;
    top: 1%;
    left: 1%;
}

.cybr-btn__text {
    color: var(--color);
    display: block;
    height: 100%;
    width: 100%;
    position: relative;
    z-index: 2;
    white-space: nowrap;
}

.cybr-btn__text:after {
    display: none;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    position: absolute;
    content: attr(data-text);
    color: var(--color);
    filter: brightness(1);
    -webkit-animation: shimmy-text 2s infinite alternate ease-in-out;
    animation: shimmy-text 2s infinite alternate ease-in-out;
    text-shadow: 2px 2px var(--shadow-primary), -2px -2px var(--shadow-secondary);
}

.cybr-btn:after {
    content: 'R25';
    position: absolute;
    padding: 10px;
    letter-spacing: 1px;
    padding: 1px 4px;
    line-height: 1;
    bottom: -5%;
    right: 5%;
    background: var(--shadow-secondary);
    color: var(--black);
    font-size: var(--label-size);
    box-shadow: 2px 0 1px 0 inset var(--shadow-primary);
}

@-webkit-keyframes shimmy-text {
    0% {
        -webkit-clip-path: inset(2% 0 95% 0);
        clip-path: inset(2% 0 95% 0);
    }

    2%,
    8% {
        -webkit-clip-path: inset(78% 0 0 0);
        clip-path: inset(78% 0 0 0);
        transform: translate(calc(var(--shimmy-distance) * -1%), 0);
    }

    6% {
        -webkit-clip-path: inset(78% 0 0 0);
        clip-path: inset(78% 0 0 0);
        transform: translate(calc(var(--shimmy-distance) * 1%), 0);
    }

    9% {
        -webkit-clip-path: inset(78% 0 0 0);
        clip-path: inset(78% 0 0 0);
        transform: translate(0, 0);
    }

    10% {
        -webkit-clip-path: inset(44% 0 46% 0);
        clip-path: inset(44% 0 46% 0);
        transform: translate(calc(var(--shimmy-distance) * 1%), 0);
    }

    13% {
        -webkit-clip-path: inset(44% 0 46% 0);
        clip-path: inset(44% 0 46% 0);
        transform: translate(0, 0);
    }

    14%,
    21% {
        -webkit-clip-path: inset(0 0 100% 0);
        clip-path: inset(0 0 100% 0);
        transform: translate(calc(var(--shimmy-distance) * 1%), 0);
    }

    15%,
    20% {
        -webkit-clip-path: inset(40% 0 60% 0);
        clip-path: inset(40% 0 60% 0);
        transform: translate(calc(var(--shimmy-distance) * 1%), 0);
    }

    25% {
        -webkit-clip-path: inset(40% 0 15% 0);
        clip-path: inset(40% 0 15% 0);
        transform: translate(calc(var(--shimmy-distance) * 1%), 0);
    }

    30% {
        -webkit-clip-path: inset(40% 0 15% 0);
        clip-path: inset(40% 0 15% 0);
        transform: translate(calc(var(--shimmy-distance) * -1%), 0);
    }

    35%,
    45% {
        -webkit-clip-path: inset(63% 0 20% 0);
        clip-path: inset(63% 0 20% 0);
        transform: translate(calc(var(--shimmy-distance) * -1%));
    }

    40% {
        -webkit-clip-path: inset(63% 0 20% 0);
        clip-path: inset(63% 0 20% 0);
        transform: translate(calc(var(--shimmy-distance) * 1%));
    }

    50% {
        -webkit-clip-path: inset(63% 0 20% 0);
        clip-path: inset(63% 0 20% 0);
        transform: translate(0, 0);
    }

    55% {
        -webkit-clip-path: inset(0 0 90% 0);
        clip-path: inset(0 0 90% 0);
        transform: translate(calc(var(--shimmy-distance) * 1%), 0);
    }

    60% {
        -webkit-clip-path: inset(0 0 90% 0);
        clip-path: inset(0 0 90% 0);
        transform: translate(0, 0);
    }

    31%,
    61%,
    100% {
        -webkit-clip-path: inset(0 0 100% 0);
        clip-path: inset(0 0 100% 0);
    }
}

@keyframes shimmy-text {
    0% {
        -webkit-clip-path: inset(2% 0 95% 0);
        clip-path: inset(2% 0 95% 0);
    }

    2%,
    8% {
        -webkit-clip-path: inset(78% 0 0 0);
        clip-path: inset(78% 0 0 0);
        transform: translate(calc(var(--shimmy-distance) * -1%), 0);
    }

    6% {
        -webkit-clip-path: inset(78% 0 0 0);
        clip-path: inset(78% 0 0 0);
        transform: translate(calc(var(--shimmy-distance) * 1%), 0);
    }

    9% {
        -webkit-clip-path: inset(78% 0 0 0);
        clip-path: inset(78% 0 0 0);
        transform: translate(0, 0);
    }

    10% {
        -webkit-clip-path: inset(44% 0 46% 0);
        clip-path: inset(44% 0 46% 0);
        transform: translate(calc(var(--shimmy-distance) * 1%), 0);
    }

    13% {
        -webkit-clip-path: inset(44% 0 46% 0);
        clip-path: inset(44% 0 46% 0);
        transform: translate(0, 0);
    }

    14%,
    21% {
        -webkit-clip-path: inset(0 0 100% 0);
        clip-path: inset(0 0 100% 0);
        transform: translate(calc(var(--shimmy-distance) * 1%), 0);
    }

    15%,
    20% {
        -webkit-clip-path: inset(40% 0 60% 0);
        clip-path: inset(40% 0 60% 0);
        transform: translate(calc(var(--shimmy-distance) * 1%), 0);
    }

    25% {
        -webkit-clip-path: inset(40% 0 15% 0);
        clip-path: inset(40% 0 15% 0);
        transform: translate(calc(var(--shimmy-distance) * 1%), 0);
    }

    30% {
        -webkit-clip-path: inset(40% 0 15% 0);
        clip-path: inset(40% 0 15% 0);
        transform: translate(calc(var(--shimmy-distance) * -1%), 0);
    }

    35%,
    45% {
        -webkit-clip-path: inset(63% 0 20% 0);
        clip-path: inset(63% 0 20% 0);
        transform: translate(calc(var(--shimmy-distance) * -1%));
    }

    40% {
        -webkit-clip-path: inset(63% 0 20% 0);
        clip-path: inset(63% 0 20% 0);
        transform: translate(calc(var(--shimmy-distance) * 1%));
    }

    50% {
        -webkit-clip-path: inset(63% 0 20% 0);
        clip-path: inset(63% 0 20% 0);
        transform: translate(0, 0);
    }

    55% {
        -webkit-clip-path: inset(0 0 90% 0);
        clip-path: inset(0 0 90% 0);
        transform: translate(calc(var(--shimmy-distance) * 1%), 0);
    }

    60% {
        -webkit-clip-path: inset(0 0 90% 0);
        clip-path: inset(0 0 90% 0);
        transform: translate(0, 0);
    }

    31%,
    61%,
    100% {
        -webkit-clip-path: inset(0 0 100% 0);
        clip-path: inset(0 0 100% 0);
    }
}


.center {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: prespective(1000px) translate(-50%, -50%);
    transform: skewY(15deg);
    transition: 0.5s;
}

.center:hover {
    transform: prespective(1000px) translate(-50%, -50%);
    transform: skewY(0deg);
}

.center h1 span {
    position: absolute;
    top: 0;
    left: 0;
    transform: translate(-50%, -50%);
    margin: 0;
    padding: 0;
    text-transform: uppercase;
    font-size: 12em;
    color: #ff3737;
    transform-style: preserve-3d;
    transition: 0.8s;
}

.center h1 span:nth-child(1) {
    clip-path: polygon(0 0, 100% 0, 100% 45%, 0 45%);
}



.center h1 span:nth-child(2) {
    color: #f0f0f0;
    transform: translate(-50%, -50%) skewX(-60deg);
    left: -38px;
    clip-path: polygon(0 45%, 100% 45%, 100% 55%, 0 55%);
}

.center h1 span:nth-child(3) {
    transform: translate(-50%, -50%) skewY(0deg);
    left: -76px;
    clip-path: polygon(0 55%, 100% 55%, 100% 100%, 0 100%);
}

.center:hover h1 span:nth-child(2),
.center:hover h1 span:nth-child(3) {
    transform: translate(-50%, -50%) skewX(0deg);
    left: 0;
    color: #fff;
}

.bg {
    background-image: url(../img//Group.jpg);
}

.mt {
    margin-left: 45em;
}
</style>
