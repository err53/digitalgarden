---
{"dg-publish":true,"permalink":"/laplace-transform/"}
---

<style>
.container {font-family: sans-serif; text-align: center;}
.button-wrapper button {z-index: 1;height: 40px; width: 100px; margin: 10px;padding: 5px;}
.excalidraw .App-menu_top .buttonList { display: flex;}
.excalidraw-wrapper { height: 800px; margin: 50px; position: relative;}
:root[dir="ltr"] .excalidraw .layer-ui__wrapper .zen-mode-transition.App-menu_bottom--transition-left {transform: none;}
</style><script src="https://unpkg.com/react@17/umd/react.production.min.js"></script><script src="https://unpkg.com/react-dom@17/umd/react-dom.production.min.js"></script><script type="text/javascript" src="https://unpkg.com/@excalidraw/excalidraw@0.12.0/dist/excalidraw.production.min.js"></script><div id="Drawing_2023-03-06_1144.14.excalidraw.md1"></div><script>(function(){const InitialData={"type":"excalidraw","version":2,"source":"https://excalidraw.com","elements":[{"id":"5jdfQzVT165rcxRkiqcZu","type":"ellipse","x":-224.4296875,"y":-237.828125,"width":122,"height":122,"angle":0,"strokeColor":"#000000","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"roundness":{"type":2},"seed":1855780253,"version":88,"versionNonce":1881561725,"isDeleted":false,"boundElements":[{"type":"text","id":"CuzMe8Z6"},{"id":"k0O0AUR3qZxXGlYx95qKz","type":"arrow"},{"id":"P3I8dHm_niWo9eYoxB20U","type":"arrow"}],"updated":1678121107910,"link":null,"locked":false},{"id":"CuzMe8Z6","type":"text","x":-194.9296875,"y":-201.828125,"width":63,"height":50,"angle":0,"strokeColor":"#000000","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"roundness":null,"seed":1150578323,"version":44,"versionNonce":1832683091,"isDeleted":false,"boundElements":null,"updated":1678121086491,"link":null,"locked":false,"text":"\"Nice\" \nODEs","rawText":"\"Nice\" ODEs","fontSize":20,"fontFamily":1,"textAlign":"center","verticalAlign":"middle","baseline":43,"containerId":"5jdfQzVT165rcxRkiqcZu","originalText":"\"Nice\" ODEs"},{"id":"VMw2yBPHGEPX9XlNRFBA7","type":"ellipse","x":107.24609375,"y":-236.3046875,"width":122,"height":122,"angle":0,"strokeColor":"#000000","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"roundness":{"type":2},"seed":939395869,"version":60,"versionNonce":2119640605,"isDeleted":false,"boundElements":[{"type":"text","id":"xrWT7ZSp"},{"id":"k0O0AUR3qZxXGlYx95qKz","type":"arrow"},{"id":"P3I8dHm_niWo9eYoxB20U","type":"arrow"}],"updated":1678121107910,"link":null,"locked":false},{"id":"xrWT7ZSp","type":"text","x":119.74609375,"y":-212.8046875,"width":97,"height":75,"angle":0,"strokeColor":"#000000","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"roundness":null,"seed":1207292413,"version":32,"versionNonce":1939060733,"isDeleted":false,"boundElements":null,"updated":1678121081892,"link":null,"locked":false,"text":"Solving \nAlgebraic \nEquations","rawText":"Solving Algebraic Equations","fontSize":20,"fontFamily":1,"textAlign":"center","verticalAlign":"middle","baseline":68,"containerId":"VMw2yBPHGEPX9XlNRFBA7","originalText":"Solving Algebraic Equations"},{"id":"k0O0AUR3qZxXGlYx95qKz","type":"arrow","x":-113.03125,"y":-232.91015625,"width":229.5078125,"height":27.1328125,"angle":0,"strokeColor":"#000000","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"roundness":{"type":2},"seed":2004089949,"version":141,"versionNonce":1509798845,"isDeleted":false,"boundElements":[{"type":"text","id":"0DuzEsTa"}],"updated":1678121094898,"link":null,"locked":false,"points":[[0,0],[117.3828125,-23.96875],[229.5078125,3.1640625]],"lastCommittedPoint":null,"startBinding":{"elementId":"5jdfQzVT165rcxRkiqcZu","focus":-0.7354959086804205,"gap":14.4002435776396},"endBinding":{"elementId":"VMw2yBPHGEPX9XlNRFBA7","focus":0.6678368272214282,"gap":14.126234301489276},"startArrowhead":null,"endArrowhead":"arrow"},{"id":"0DuzEsTa","type":"text","x":-2.1484375,"y":-269.37890625,"width":13,"height":25,"angle":0,"strokeColor":"#000000","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"roundness":null,"seed":1842727155,"version":2,"versionNonce":347484819,"isDeleted":false,"boundElements":null,"updated":1678121099168,"link":null,"locked":false,"text":"L","rawText":"L","fontSize":20,"fontFamily":1,"textAlign":"center","verticalAlign":"middle","baseline":18,"containerId":"k0O0AUR3qZxXGlYx95qKz","originalText":"L"},{"id":"P3I8dHm_niWo9eYoxB20U","type":"arrow","x":118.890625,"y":-122.41796875,"width":226.81640625,"height":22.97265625,"angle":0,"strokeColor":"#000000","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"roundness":{"type":2},"seed":51931187,"version":120,"versionNonce":1505708989,"isDeleted":false,"boundElements":[{"type":"text","id":"UKv277BM"}],"updated":1678121111128,"link":null,"locked":false,"points":[[0,0],[-109.078125,17.80859375],[-226.81640625,-5.1640625]],"lastCommittedPoint":null,"startBinding":{"elementId":"VMw2yBPHGEPX9XlNRFBA7","focus":-0.7252941316692973,"gap":11.339251555941814},"endBinding":{"elementId":"5jdfQzVT165rcxRkiqcZu","focus":0.6181205475154115,"gap":13.20149162006502},"startArrowhead":null,"endArrowhead":"arrow"},{"id":"UKv277BM","type":"text","x":-9.1875,"y":-117.109375,"width":38,"height":25,"angle":0,"strokeColor":"#000000","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"roundness":null,"seed":2062987507,"version":9,"versionNonce":983631165,"isDeleted":false,"boundElements":null,"updated":1678121116547,"link":null,"locked":false,"text":"L^-1","rawText":"L^-1","fontSize":20,"fontFamily":1,"textAlign":"center","verticalAlign":"middle","baseline":18,"containerId":"P3I8dHm_niWo9eYoxB20U","originalText":"L^-1"}],"appState":{"theme":"light","viewBackgroundColor":"#ffffff","currentItemStrokeColor":"#000000","currentItemBackgroundColor":"transparent","currentItemFillStyle":"hachure","currentItemStrokeWidth":1,"currentItemStrokeStyle":"solid","currentItemRoughness":1,"currentItemOpacity":100,"currentItemFontFamily":1,"currentItemFontSize":20,"currentItemTextAlign":"left","currentItemStartArrowhead":null,"currentItemEndArrowhead":"arrow","scrollX":296.97265625,"scrollY":473.26171875,"zoom":{"value":1},"currentItemRoundness":"round","gridSize":null,"colorPalette":{}},"files":{}};InitialData.scrollToContent=true;App=()=>{const e=React.useRef(null),t=React.useRef(null),[n,i]=React.useState({width:void 0,height:void 0});return React.useEffect(()=>{i({width:t.current.getBoundingClientRect().width,height:t.current.getBoundingClientRect().height});const e=()=>{i({width:t.current.getBoundingClientRect().width,height:t.current.getBoundingClientRect().height})};return window.addEventListener("resize",e),()=>window.removeEventListener("resize",e)},[t]),React.createElement(React.Fragment,null,React.createElement("div",{className:"excalidraw-wrapper",ref:t},React.createElement(ExcalidrawLib.Excalidraw,{ref:e,width:n.width,height:n.height,initialData:InitialData,viewModeEnabled:!0,zenModeEnabled:!0,gridModeEnabled:!1})))},excalidrawWrapper=document.getElementById("Drawing_2023-03-06_1144.14.excalidraw.md1");ReactDOM.render(React.createElement(App),excalidrawWrapper);})();</script>


> [!abstract] Definition
> Assume that $f(t)$ is a functinon defined for $t \geq 0$.
> The Laplace Transform of $f$ is the function
> $$
> F(s) = \mathscr{L}\{f\} = \int_0^\infty e^{-st} f(t) dt, s > a
> $$

See also:
[[Inverse Laplace Transform\|Inverse Laplace Transform]]

#todo 
Learn standard laplace transforms!

## Linearity of the Laplace Transform
Let $f(t)$ and $g(t)$ be functions that have a Laplace Transform that exists for $s > a$, for some $a \in \mathbb{R}$.

Let $\alpha, \beta \in \mathbb{R}$ (or $\mathbb{C}$) and denote $F(s) = \mathscr{L} \{f(t)\}, G(s) = \mathscr{L}\{g(t)\}$.
Then
$$
\begin{align}
\mathscr{L}\{\alpha f(t) + \beta g(t)\}
&= \alpha \mathscr{L}\{f(t)\} + \beta \mathscr{L}\{f(t)\} & s > a \\
&= \alpha F(s) + \beta G(S) & s > a \\
\end{align}
$$

## Existence of Laplace Transform
Assume $f(t)$ is piecewise continuous on $[0, \infty)$, and of [[Exponential Order\|Exponential Order]] $\alpha$ as $t \to \infty$.
Then $\mathscr{L}\{f\}$ exists for $x > \alpha$
i.e.
$$
F(x) = \int_0^\infty e^{-st} f(t) dt
= \underbrace{\lim_{N\to\infty} \int_0^N e^{-st} f(t) dt}_{\textrm{converges for $x > \alpha$}}
$$


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/inverse-laplace-transform/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




Given $F$, assume $\exists$ another func $f$ such that $\mathscr{L}\{f\} = F \implies f = \mathscr{L}^{-1}\{F\}$

$
f(t) = \mathscr{L}^{-1}\{f(s)\}
$


</div></div>
