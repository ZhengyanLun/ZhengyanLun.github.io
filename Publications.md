---
title:  "Publications"
mathjax: true
layout: post
categories: media
---

(* corresponding authorship;      † co-authorship)

9) 

8) Zhengyan Lun, Bin Ouyang, Daniil A. Kitchaev, Raphaële J. Clément, Joseph K. Papp, Mahalingam Balasubramanian, Yaosen Tian, Teng Lei, Tan Shi, Bryan D. McCloskey, Jinhyuk Lee* , Gerbrand Ceder*, "Improved Cycling Performance of Li‐Excess Cation‐Disordered Cathode Materials upon Fluorine Substitution." Advanced Energy Materials 9.2 (2019): 1802959. [https://doi.org/10.1002/aenm.201802959](https://onlinelibrary.wiley.com/doi/abs/10.1002/aenm.201802959)

7) Jinhyuk Lee* , Daniil A. Kitchaev, Deok-Hwang Kwon, Chang-Wook Lee, Joseph K. Papp, Yi-Sheng Liu, Zhengyan Lun, Raphaële J. Clément, Tan Shi, Bryan D. McCloskey, Jinghua Guo, Mahalingam Balasubramanian, Gerbrand Ceder*, "Reversible Mn 2+/Mn 4+ double redox in lithium-excess cathode materials." Nature 556.7700 (2018): 185-190.[DOI: https://doi.org/10.1038/s41586-018-0015-4](https://www.nature.com/articles/s41586-018-0015-4)

6) Daniil A. Kitchaev* †, Zhengyan Lun†, William D. Richards, Huiwen Ji, Raphaële J. Clément, Mahalingam Balasubramanian, Deok-Hwang Kwon, Kehua Dai, Joseph K. Papp, Teng Lei, Bryan D. McCloskey, Wanli Yang, Jinhyuk Lee, Gerbrand Ceder*, "Design principles for high transition metal capacity in disordered rocksalt Li-ion cathodes." Energy & Environmental Science 11.8 (2018): 2159-2171. [DOI: 10.1039/C8EE00816G](https://pubs.rsc.org/en/content/articlehtml/2018/ee/c8ee00816g)
[2018 Energy and Environmental Science HOT Articles](https://pubs.rsc.org/en/journals/articlecollectionlanding?sercode=ee&themeid=18c9c4b5-1d5d-4ffc-9640-88e7b7c4b1eb)
Related reading: Malik, Rahul. ["Frontiers of Chemical Space." Joule 2.8 (2018): 1403-1404.](https://www.sciencedirect.com/science/article/pii/S2542435118303453)

5) Yang Yang, Zhiyu Lin, Shiqi Gao, Jianwei Su, Zhengyan Lun, Guoliang Xia, Jitang Chen, Ruirui Zhang, Qianwang Chen*. "Tuning electronic structures of nonprecious ternary alloys encapsulated in graphene layers for optimizing overall water splitting activity." Acs Catalysis 7.1 (2017): 469-479. [DOI: 10.1021/acscatal.6b02573.](https://pubs.acs.org/doi/abs/10.1021/acscatal.6b02573)

4) Yang Yang, Fangcai Zheng, Guoliang Xia, Zhengyan Lun, Qianwang Chen*. "Experimental and theoretical investigations of nitro-group doped porous carbon as a high performance lithium-ion battery anode." Journal of Materials Chemistry A 3.36 (2015): 18657-18666. [DOI: 10.1039/C5TA05676D](https://pubs.rsc.org/en/content/articlehtml/2015/ta/c5ta05676d)

3) Yang Yang, Zhengyan Lun, Guoliang Xia, Fangcai Zheng, Mengni He, Qianwang Chen*. "Non-precious alloy encapsulated in nitrogen-doped graphene layers derived from MOFs as an active and durable hydrogen evolution reaction catalyst." Energy & Environmental Science 8.12 (2015): 3563-3571. [DOI: 10.1039/C5EE02460A](https://pubs.rsc.org/en/content/articlehtml/2015/ee/c5ee02460a?casa_token=l64bWa9ooiEAAAAA:tTPxPs-01R9BFNmXWSuvbwTuLbdmLJFN7XK7gYUn38rBo1Csqb8KYwfaMXJWkhbFM0EGq8cDSy3t)

2) Xiangkai Kong, Qianwang Chen*, and Zhengyan Lun. "The influence of N‐doped carbon materials on supported Pd: enhanced hydrogen storage and oxygen reduction performance." ChemPhysChem 15.2 (2014): 344-350. [DOI:   https://doi.org/10.1002/cphc.201300907](https://chemistry-europe.onlinelibrary.wiley.com/doi/abs/10.1002/cphc.201300907)

1) Xiangkai Kong, Qianwang Chen*, and Zhengyan Lun. "Probing the influence of different oxygenated groups on graphene oxide's catalytic performance." Journal of Materials Chemistry A, 2,3 (2014): 610-613.
[DOI:  https://doi.org/10.1039/C3TA13946H](https://pubs.rsc.org/en/content/articlelanding/2014/ta/c3ta13946h/unauth)

![Swiss Alps](https://user-images.githubusercontent.com/4943215/55412536-edbba180-5567-11e9-9c70-6d33bca3f8ed.jpg)


## MathJax

You can enable MathJax by setting `mathjax: true` on a page or globally in the `_config.yml`. Some examples:

[Euler's formula](https://en.wikipedia.org/wiki/Euler%27s_formula) relates the  complex exponential function to the trigonometric functions.

$$ e^{i\theta}=\cos(\theta)+i\sin(\theta) $$

The [Euler-Lagrange](https://en.wikipedia.org/wiki/Lagrangian_mechanics) differential equation is the fundamental equation of calculus of variations.

$$ \frac{\mathrm{d}}{\mathrm{d}t} \left ( \frac{\partial L}{\partial \dot{q}} \right ) = \frac{\partial L}{\partial q} $$

The [Schrödinger equation](https://en.wikipedia.org/wiki/Schr%C3%B6dinger_equation) describes how the quantum state of a quantum system changes with time.

$$ i\hbar\frac{\partial}{\partial t} \Psi(\mathbf{r},t) = \left [ \frac{-\hbar^2}{2\mu}\nabla^2 + V(\mathbf{r},t)\right ] \Psi(\mathbf{r},t) $$

## Code

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

## Gists

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

