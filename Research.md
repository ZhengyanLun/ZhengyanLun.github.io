---
title:  "Research interests"
mathjax: true
layout: post
categories: media
---



## Design and synthesis of next-generation energy storage materials

The tremendous success and growth of energy storage technology in a broad range of applications have long-lasting and far-reaching influence on our human society. Li-ion technology is so far the most promising and optimized component within the energy storage technology frame, which can further be divided into several sub-catagories, i.e., cathodes, anodes and electrolytes. Not only should we further enhance the capacity, rate capability and cycle life of various components, but also seek for less resource-constrained candidates for energy storage.

I am experienced in the design and synthesis of various class of energy storage materials, especially cation-disordered rocksalt (DRX) materials and Ni-rich NMC cathodes, the optimization of which can be achieved from the delicate manipulation of overall composition, long-range crystal structure and local short-range ordering as well.


You can enable MathJax by setting `mathjax: true` on a page or globally in the `_config.yml`. Some examples:

[Euler's formula](https://en.wikipedia.org/wiki/Euler%27s_formula) relates the  complex exponential function to the trigonometric functions.

$$ e^{i\theta}=\cos(\theta)+i\sin(\theta) $$

The [Euler-Lagrange](https://en.wikipedia.org/wiki/Lagrangian_mechanics) differential equation is the fundamental equation of calculus of variations.

$$ \frac{\mathrm{d}}{\mathrm{d}t} \left ( \frac{\partial L}{\partial \dot{q}} \right ) = \frac{\partial L}{\partial q} $$

The [Schrödinger equation](https://en.wikipedia.org/wiki/Schr%C3%B6dinger_equation) describes how the quantum state of a quantum system changes with time.

$$ i\hbar\frac{\partial}{\partial t} \Psi(\mathbf{r},t) = \left [ \frac{-\hbar^2}{2\mu}\nabla^2 + V(\mathbf{r},t)\right ] \Psi(\mathbf{r},t) $$

## Development and application of advanced characterization techniques

The electrochemical performance of energy storage materials are primarily related to the structure of the materials and the reaction kinetics during operation. One must rely on various advanced characterization techniques, both *in-situ* (i.e., tracking the structure / kinetic information during the electrochemical cycling in real time) and *ex-situ* (i.e., stopping the components at different state of charge and performing various characterizations). I am a fan of developing and applying various techniques to probe the structure-property relationships and reaction kinetics in energy storage materials, including, but not limited to the following:

### X-ray diffraction (XRD)

XRD is a traditional, yet powerful tool to track the long-range crystal structure of the materials. *Operando* XRD provides valuable information of the phase behavior during the electrochemical cycling of energy storage materials in real time, and can be applied to understand the stability and reaction kinetics of the material upon cycling. 

### Pair-distribution function (PDF)

PDF is a bulk-sensitive local structure characterization technique, which can probe the local 


### Transmission electron microscopy (TEM)

### Solid-state nuclear magnetic resonance spectroscopy (ssNMR)

### X-ray absorption spectroscopy (XAS)

### Ultrafast interferometric scattering (iSCAT) optical microscopy


Embed code by putting `{{ "{% highlight language " }}%}` `{{ "{% endhighlight " }}%}` blocks around it. Adding the parameter `linenos` will show source lines besides the code.

{% highlight c %}

static void asyncEnabled(Dict* args, void* vAdmin, String* txid, struct Allocator* requestAlloc)
{
    struct Admin* admin = Identity_check((struct Admin*) vAdmin);
    int64_t enabled = admin->asyncEnabled;
    Dict d = Dict_CONST(String_CONST("asyncEnabled"), Int_OBJ(enabled), NULL);
    Admin_sendMessage(&d, txid, admin);
}

{% endhighlight %}

## Investigation of the reaction mechanism of ceramic material synthesis

With the `jekyll-gist` plugin, which is preinstalled on Github Pages, you can embed gists simply by using the `gist` command:

<script src="https://gist.github.com/5555251.js?file=gist.md"></script>

## Images

Upload an image to the *assets* folder and embed it with `![title](/assets/name.jpg))`. Keep in mind that the path needs to be adjusted if Jekyll is run inside a subfolder.

A wrapper `div` with the class `large` can be used to increase the width of an image or iframe.

![Flower](https://user-images.githubusercontent.com/4943215/55412447-bcdb6c80-5567-11e9-8d12-b1e35fd5e50c.jpg)

[Flower](https://unsplash.com/photos/iGrsa9rL11o) by Tj Holowaychuk

## Embedded content

You can also embed a lot of stuff, for example from YouTube, using the `embed.html` include.

{% include embed.html url="https://www.youtube.com/embed/_C0A5zX-iqM" %}

