# cmpsci-403-homework-6--perception-mechanics-dynamics-and-control-solved
**TO GET THIS SOLUTION VISIT:** [CMPSCI 403 Homework 6- Perception, Mechanics, Dynamics, and Control Solved](https://www.ankitcodinghub.com/product/cmpsci-403-introduction-to-robotics-perception-mechanics-dynamics-and-control-solved-5/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109282&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPSCI 403 Homework 6- Perception, Mechanics, Dynamics, and Control Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
HW06

Using the example given in class as a guide, derive the equations of motion (in Matlab) for the double pendulum with parameter definitions as in the figure below. A torque τ1 with vector τ1kˆ (where kˆ = ˆi × ˆj) acts between the base and body 1, and a torque τ2 with vector τ2kˆ acts between body 1 and body 2. Assume gravity g = 9.81m/s2 in the −ˆj direction. Write a function to simulate the double pendulum. Provide a copy of your working code.

Figure 1: Double pendulum and parameter definitions.

1. With τ1 = τ2 = 0, solve the initial boundary value problem from the initial condition

θ1 = 3rad, θ2 = 0rad, θ˙1 = θ˙2 = 0rad/s

on the time interval t = [0s, 7s]. Use parameters m1 = m2 = 1kg, I1 = I2 = 0.05kg·m2, l1 = 1m, l2 = 0.5m, c1 = 0.5m, c2 = .25m.

Plot θ1(t) and θ2(t). Does the solution display any repetitive and predictable patterns?

2. Plot the total system energy (T + V ) over the same interval. Verify energy conservation (You will see almost constant energy having a small drift).

3. (Optional) Derive the equations again considering the addition of three springs with potential energies

The vector r0 = [rx ry]T represents the attachment point for the last spring.

4. (Optional) After verifying energy conservation of your equations, simulate the system with

κ1 = κ2 = 10Nm/rad, k3 = 50N/m θ1,0 = θ2,0 = 0, l0 = 0, rx = 0m, ry = 0.5m

Apply τ1 = −θ˙1 and τ2 = −θ˙2 and use the same initial state as in step 2.

1
