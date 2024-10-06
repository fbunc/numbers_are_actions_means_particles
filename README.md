## Rationality and periodicity - Continuos Time or Discrete time?

Well, time is what it is. It might be a continuous phenomena, as a universal wave that is composed of individual packets of information or "monads". If you read about the idea of phonons, and then about the idea of photons all makes more sense. Vibrational energy typically needs a medium we feel familiar with, like air, electro-magnetic waves do not need (In principle) a medium to propagate, it's said they propagate through another mathematical object called space-time. 

So waves propagate through a Galilean space time. I'm not a physicist , so I'd love to be corrected by someone that really knows about these things. 

It's useful to imagine monads as dynamic mirrors that produce a specific set of musical notes for every place of space and happening during an unimaginable fast and powerful set of Time's quartz ticks. 

When we write Time we mean the ontological entity we are playing as a character in our Math fan fiction story, but moments of time are just snapshots of whatever is happening from the micro scales to the large scales of the toy universe. 

It depends on what we are looking at, if we are interested on the energy of a process, or it's biological evolution, or maybe just play in the most general way, the group theory way, and let math and it's symmetries guide you through the physical intuitions you can't completely grasp, and would produce brain overflow if every ad-hoc application of symmetry is thought at the same time.

Group theory allows us to Stop Time, make it go Back and Forward at our on pace, and for our own set of ontological axioms. 

Given N monads labeled by a specific colormap, created as a one to one mapping to the natural numbers and describing  a curve in space $\vec{\mathbf{X_n}}$ , created by a single array of complex numbers $Z_n$ that is created **recursively** . 

$$\vec{\mathbf{X_n}}=(u_n,v_n,w_n)$$

Considering:
$$t  \in \space \mathbb{R}$$
$$n \geq 0 \in \space \mathbb{N}$$

$$T_o,T,T_s  \in \space \mathbb{Q}$$


$$k,p,q  \in \space \mathbb{Z}$$

$$r_k=\begin{cases}
0 &  k  < 0 \\
r_{k-1}+\Delta r_o & \space k \geq 0 \text{ and } k \equiv 0 \pmod{M} \\
r_{k-1} & \space   k > 0 \text{ and } k \not\equiv 0 \pmod{M}
\end{cases}$$

In the most general case $r_k$ is a complex number, meaning it can contain some initial conditions encoded as a phase along with some twists on the fundamental circular wave propagation pattern of the presented simplification. In this educational simplification, we use $\Delta r_o \in \mathbb{Q}$ to make our ontological playground ideas consistent with the simulations we are going to see about them. 


For a continuous time $t$ we can imagine a simple function as a 2D number as $\theta^t$:

$$\theta^t=e^{\frac{2\pi i}{T}t}$$

For a discrete time $n$ we can imagine a similar 2D number as a function like $\omega^n$: 

$$\omega^n=\omega_o^n=e^{\frac{2\pi i}{T_o}n}$$

$T_o$ completely governs the behavior of $\omega$ and can be interpreted as restricted by our sampling frequency $f_s=1/T_s$


### Nyquist Shannon Theorem

If we satisfy a **sufficient** condition given by Nyquist Shannon Theorem, we can safely assume in ideal conditions that we are able to avoid aliasing using a sampling frequency at least two times larger than the highest frequency present in the sampled signal.

Claude S. taught us that if $f_s\geq 2f$ we have a sufficient amount of samples to be able to reconstruct $\theta^t$ from our sampled $\omega^n$ function without aliasing. 


$$\theta^{nT_s}=\omega^{n}$$

**Sufficient** means that the Theorem says nothing about particular cases where using $f_s>kf$ for a positive $k \leq 1$ might produce results where reconstruction is still possible. This idea is used in MRI technology for example, in radial sampling scenarios where sparsity becomes important as a parameter defining the sampling period. 


So what about the periodicity of the continuos time function and the related discrete time sequence? 

$$\theta^{t+T}=\theta^{t}\theta^{T}=\theta^t$$


$$\omega^{n+P}=\omega^{n}\omega^{P}=\omega^n$$


But in general, we will see we need to consider our $\omega$ as a family over all the integers:

$$\omega=e^{\frac{2\pi i}{T_o}}$$

$$T_o=\frac{T}{T_s}=\frac{f_s}{f}=\frac{p}{q}$$



So the period $P$ has to be restricted by the selection of the following parameters being $k,k_o \in \mathbb{Z}$:

$$\omega^{P}=\omega^{k_oT_o}=e^{2 \pi ik}$$

$$P=k_o T_o$$

This is valid if we write $k_o=kq$:

$$P=k q T_o=k p$$

$$p=q\frac{T}{T_s}$$

$$p=q\frac{f_s}{f}$$

So we have this simple conclusion, the periods of the discrete time sequence are multiples of $p$ if we assume $T/T_s$ and $f_s/f$ to be  rational numbers. But $f$ might not be rational, or the selected sampling frequency could have components that make it drift over time, so we might want an integer value for $f_s$ but not achieve-it in reality. 



### The drifting of the irrationals

If we imagine a case where $T$ is not a rational number, the discrete time sequence will lose it's classical periodicity, if we try to approximate the effect, we will see drifting $\text{m-gons}$ on each subsequent orbit not quite going back to the same phase . 

But if you wait long enough and choose the right perspective, you start to see the almost periodicity emerge. 

Choosing the right parameters we can sync an irrational to make it correspond for a selected scale to an integer we will call $M_c$

I've been told by more than one mathematician that I can prove this, but I'm not sure what they mean. I'm not familiar with doing mathematical proofs. 

I mean I know what induction is, and most of the time feels like a path to show something that is already obvious if you accepted the axioms and understood their consequences , 


### General cases vs the simple example case

The general $Z[n,k]$ family of sequences: 

$$\omega_k=e^{\frac{2\pi i}{T_k}}$$

$$Z[n,k]=r_n\omega_k^n$$

$$Z^*[n,k]=r_n\omega_k^{-n}$$


The identity $Z_n$ sequence:

$$Z_n=r_n\omega^{n}$$

$$Z^*_n=r_n\omega^{-n}$$

### Information representation using the idea of circular histograms or discrete-time orbits to represent Almost Periodic functions

The color $C_n$ in these examples is based on  "hsv" or "coolwarm" colormaps with $M_c$ colors. 

We use the color as a simple way to encode 3 extra dimensions given by the hue, saturation and value , or the red, green and blue components of the representation. So in these examples we can imagine the color following a function proportional to Time's most simple evolution, or as symbols coming from a roulette wheel with $M$ slots you need to organize in time because you suspect there might be some "almost-periodicity" associated to that set of symbols you are receiving, you know they are not real roulette long term sets of data, they look like roulette but finally you discover they follow an specific pattern like for example:

$$ X_{o}=\frac{p_o}{q_o} \in \mathbb{Q}  \space [0,1]$$

$$X_{n+1}\equiv (2+\delta) X_{n} \pmod{1}$$ 

$\delta=\alpha \space 10^{-15}$  maintains the "almost-periodicity" for a much larger number of iterations avoiding binary shifting problems



## Coloring used in the examples

For the first set of plots expect a simple $\hat{C}(n)=n$ so we start with the initial blueprints , the idea of Time laying out it's strategy to follow Symbols (information) thoughts. 

$$C_n \equiv \hat{C}(n) \pmod{M_{c}}$$





## Cartesian Coordinates

Cartesian coordinates for the resulting set of sequences describing a curve in space:

$$\vec{\mathbf{X_n}}=(u_n,v_n,w_n)$$


$$\Omega_o=\frac{2\pi }{T_o}$$

$$\Omega_k=\frac{2\pi }{T_k}$$

In these examples we choose a simple combination of arrays to keep the first plots more intuitive following the color as a modular counting process. 

$$(\mathbf{i}, \mathbf{j}, \mathbf{k})$$

The main string:

$$\vec{\mathbf{X_n}}=U(Z_n)\mathbf{i} + V(Z_n)\mathbf{j}+ W(Z_n)\mathbf{k}$$



$$u_n=U(Z_n)=\frac{1}{2}(Z_n+Z^*_n)=r_n cos(\Omega_k n)$$

$$v_n=V(Z_n)=\frac{1}{2i}(Z_n-Z^*_n)=r_n sin(\Omega_k n)$$

$$w_n=W(Z_n)=log_{2}(|Z_n|)$$

And the RGB vector representation of the color $C_n$ : 
$$\vec{\mathbf{C_n}}=R(Z_n)\mathbf{i} + G(Z_n)\mathbf{j}+ B(Z_n)\mathbf{k}$$

Or in HSV, maybe our context allow us to think the color as representing hue, saturation and value. 

$$\vec{\mathbf{C_n}}=H(Z_n)\mathbf{i} + S(Z_n)\mathbf{j}+ V(Z_n)\mathbf{k}$$


### General examples of 2D representations of sequence sets

For a general case consider $S_n \in \mathbb{Q}$ and $M \in \mathbb{N} $.

Consider:

$$K_n, \space H_n,\space \zeta_n, \space \tau_n \in \mathbb{C}$$

$$|K_n|\ll |\tau_n| $$

In the examples we will see plots using a fixed $K_n=K$, but in general cases we need to adjust this value following a specific set of rules that can be inferred from data, or designed for a specific purpose. 

#### Discrete time orbits

A discrete-time orbit with an associated symbol :

$$\tau_n=|\tau_n|\omega ^n $$

$$\zeta_n=\hat{S}(n,S_n)=K_n\space e^{\frac{2 \pi i}{M}S_n}$$

$$\xi_n=\tau_n + \zeta_n$$


#### Rotating Histograms

$$H_n=K_n \zeta_n$$

In the following examples $K_n=K \space log_b(n)$ :


$$H_n=K \space log_b(n) \space e^{\frac{2 \pi i}{M}S_n}$$