# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.




<!DOCTYPE html>
<!-- saved from url=(0022)http://localhost:5173/ -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <script type="module">import { injectIntoGlobalHook } from "/@react-refresh";
injectIntoGlobalHook(window);
window.$RefreshReg$ = () => {};
window.$RefreshSig$ = () => (type) => type;</script>

    <script type="module" src="./cardsproject_files/client"></script>

    
    <link rel="icon" type="image/svg+xml" href="http://localhost:5173/vite.svg">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>cardsproject</title>
  <style type="text/css" data-vite-dev-id="C:/Users/Aditta/Desktop/ReactPro/Cardsproject/src/index.css">* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'helvetica neue';
}
html,
body {
    height: 100%;
    width: 100%;
}

.parent{
  min-height: 100vh;
  width: 100%;
  background-color: #111;
  padding: 30px;
  display: flex;
  gap: 30px;
  flex-wrap: wrap;
}

.card{
  height: 330px;
  width: 280px;
  background-color: #fff;
  border-radius: 30px;
  padding: 30px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
.card .top{
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  margin-bottom: 30px;
}

.top img{
  height: 42px;
  width: 42px;
  border-radius: 50%;
  border: 1px solid #dadada;
  padding: 3px;
  object-fit: cover;
}
.top button{
  display: flex;
  align-items: center;
  border: 1px solid #dadada;
  padding: 3px 6px;
  font-size: 10px;
  border-radius: 5px;
  gap: 3px;
  background-color: transparent;
  color: #8b8b8b;
}


.center{
}

.center h3{
  font-size: 16px;
  font-weight: 500;
}
.center h3 span{
  font-size: 9px;
  font-weight: 400;
  color: #aeaeae;
}

.center h2{
  font-size: 21px;
  font-weight: 500;

}
.center .tag{
  display: flex;
  margin-top: 10px;
  gap: 5px;
}
.center .tag h4{
  font-size: 10px;
  background-color: #e4e4e4;
  color: #202020;
  font-weight: 500;
  padding: 4px 8px;
  border-radius: 3px;
}
.bottom{
  display: flex;
  align-items: center;
  justify-content: space-between;
  border-top: 1.5px solid #d7d7d7ce;
  padding-top: 15px;
}

.bottom button{
  background-color: rgb(18, 18, 18);
  color: white;
  padding: 7px 16px;
  border: none;
  border-radius: 5px;
  font-size: 12px;
  column-width: 600;
}

.bottom h3{
  font-size: 17px;
  font-weight: 500;
  margin-bottom: 4px;
}
.bottom p{
  font-size: 10px;
  color: #8b8b8b;
}</style></head>
  <body>
    <div id="root"><div class="parent"><div><div class="card"><div><div class="top"><img alt="nachioooooo" src="./cardsproject_files/meta_PNG12.png"><button>Save <svg xmlns="http://www.w3.org/2000/svg" width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-bookmark" aria-hidden="true"><path d="m19 21-7-4-7 4V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v16z"></path></svg> </button></div><div class="center"><h3>Meta <span>5 days ago</span></h3><h2>Frontend Engineer</h2><div class="tag"><h4>Full Time</h4><h4>Junior Level</h4></div></div></div><div class="bottom"><div><h3>$65/hour</h3><p>Mumbai, India</p></div><button>Apply Now</button></div></div></div><div><div class="card"><div><div class="top"><img alt="nachioooooo" src="./cardsproject_files/amazon-logo-on-transparent-background-free-vector.jpg"><button>Save <svg xmlns="http://www.w3.org/2000/svg" width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-bookmark" aria-hidden="true"><path d="m19 21-7-4-7 4V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v16z"></path></svg> </button></div><div class="center"><h3>Amazon <span>2 weeks ago</span></h3><h2>Backend Developer</h2><div class="tag"><h4>Full Time</h4><h4>Mid Level</h4></div></div></div><div class="bottom"><div><h3>$70/hour</h3><p>Mumbai, India</p></div><button>Apply Now</button></div></div></div><div><div class="card"><div><div class="top"><img alt="nachioooooo" src="./cardsproject_files/8ed3d547-94ff-48e1-9f20-8c14a7030a02_2000x2000.jpg"><button>Save <svg xmlns="http://www.w3.org/2000/svg" width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-bookmark" aria-hidden="true"><path d="m19 21-7-4-7 4V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v16z"></path></svg> </button></div><div class="center"><h3>Apple <span>3 weeks ago</span></h3><h2>iOS Developer</h2><div class="tag"><h4>Part Time</h4><h4>Senior Level</h4></div></div></div><div class="bottom"><div><h3>$90/hour</h3><p>Mumbai, India</p></div><button>Apply Now</button></div></div></div><div><div class="card"><div><div class="top"><img alt="nachioooooo" src="./cardsproject_files/Netflix-Symbol.png"><button>Save <svg xmlns="http://www.w3.org/2000/svg" width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-bookmark" aria-hidden="true"><path d="m19 21-7-4-7 4V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v16z"></path></svg> </button></div><div class="center"><h3>Netflix <span>10 days ago</span></h3><h2>Machine Learning Engineer</h2><div class="tag"><h4>Full Time</h4><h4>Senior Level</h4></div></div></div><div class="bottom"><div><h3>$110/hour</h3><p>Mumbai, India</p></div><button>Apply Now</button></div></div></div><div><div class="card"><div><div class="top"><img alt="nachioooooo" src="./cardsproject_files/Google__G__logo.svg.png"><button>Save <svg xmlns="http://www.w3.org/2000/svg" width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-bookmark" aria-hidden="true"><path d="m19 21-7-4-7 4V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v16z"></path></svg> </button></div><div class="center"><h3>Google <span>1 week ago</span></h3><h2>Cloud Solutions Architect</h2><div class="tag"><h4>Full Time</h4><h4>Mid Level</h4></div></div></div><div class="bottom"><div><h3>$85/hour</h3><p>Mumbai, India</p></div><button>Apply Now</button></div></div></div><div><div class="card"><div><div class="top"><img alt="nachioooooo" src="./cardsproject_files/Microsoft_Store-Logo.wine.png"><button>Save <svg xmlns="http://www.w3.org/2000/svg" width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-bookmark" aria-hidden="true"><path d="m19 21-7-4-7 4V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v16z"></path></svg> </button></div><div class="center"><h3>Microsoft <span>4 weeks ago</span></h3><h2>Data Scientist</h2><div class="tag"><h4>Full Time</h4><h4>Junior Level</h4></div></div></div><div class="bottom"><div><h3>$75/hour</h3><p>Mumbai, India</p></div><button>Apply Now</button></div></div></div><div><div class="card"><div><div class="top"><img alt="nachioooooo" src="./cardsproject_files/ibm-logo-1967.jpg"><button>Save <svg xmlns="http://www.w3.org/2000/svg" width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-bookmark" aria-hidden="true"><path d="m19 21-7-4-7 4V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v16z"></path></svg> </button></div><div class="center"><h3>IBM <span>2 days ago</span></h3><h2>AI Research Engineer</h2><div class="tag"><h4>Full Time</h4><h4>Senior Level</h4></div></div></div><div class="bottom"><div><h3>$95/hour</h3><p>Mumbai, India</p></div><button>Apply Now</button></div></div></div><div><div class="card"><div><div class="top"><img alt="nachioooooo" src="./cardsproject_files/Tesla-Logo-PNG-HD-Quality.png"><button>Save <svg xmlns="http://www.w3.org/2000/svg" width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-bookmark" aria-hidden="true"><path d="m19 21-7-4-7 4V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v16z"></path></svg> </button></div><div class="center"><h3>Tesla <span>6 days ago</span></h3><h2>Software Engineer</h2><div class="tag"><h4>Full Time</h4><h4>Mid Level</h4></div></div></div><div class="bottom"><div><h3>$80/hour</h3><p>Mumbai, India</p></div><button>Apply Now</button></div></div></div><div><div class="card"><div><div class="top"><img alt="nachioooooo" src="./cardsproject_files/nvidia-og-image-white-bg-1200x630.jpg"><button>Save <svg xmlns="http://www.w3.org/2000/svg" width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-bookmark" aria-hidden="true"><path d="m19 21-7-4-7 4V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v16z"></path></svg> </button></div><div class="center"><h3>NVIDIA <span>3 weeks ago</span></h3><h2>GPU Programmer</h2><div class="tag"><h4>Full Time</h4><h4>Senior Level</h4></div></div></div><div class="bottom"><div><h3>$120/hour</h3><p>Mumbai, India</p></div><button>Apply Now</button></div></div></div><div><div class="card"><div><div class="top"><img alt="nachioooooo" src="./cardsproject_files/images"><button>Save <svg xmlns="http://www.w3.org/2000/svg" width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-bookmark" aria-hidden="true"><path d="m19 21-7-4-7 4V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v16z"></path></svg> </button></div><div class="center"><h3>Oracle <span>8 days ago</span></h3><h2>Database Administrator</h2><div class="tag"><h4>Full Time</h4><h4>Mid Level</h4></div></div></div><div class="bottom"><div><h3>$70/hour</h3><p>Mumbai, India</p></div><button>Apply Now</button></div></div></div></div></div>
    <script type="module" src="./cardsproject_files/main.jsx"></script>
  

</body></html>
