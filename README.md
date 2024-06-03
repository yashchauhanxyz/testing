# StudyNotion Edtech Project
@keyframes shimmerCustom {
  0% {
    background-position: -200% 0;
  }
  100% {
    background-position: 200% 0;
  }
}

#skeleton_img,
.skeleton_img_class {
  display: block;
  background: linear-gradient(90deg, #1a1a1a 25%, #232323 50%, #1a1a1a 75%);
  background-size: 200% 100%;
  animation: shimmerCustom 1.5s infinite linear;
  z-index: 9999;
}