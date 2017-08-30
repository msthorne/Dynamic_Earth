###### Lecture \#1 - Composition of the Earth 

Just some copy/paste of stub materials that might go into such a lecture.

**1. 1D Radial profiles**
-------------------------

Seismic imaging gives us the most direct way to probe the Earth’s interior. We
will talk about how to do this when we get to seismic techniques. But, for now,
let’s just look at the 1D average structure of the Earth as determined through
seismology – with special attention to the density structure. Note, Earth’s free
oscillations (or normal modes) are particularly sensitive to the Earth’s density
structure, and hence this density model is derived from those observations.

Currently the PREM (**P**reliminary **R**eference **E**arth **M**odel) derived
by Adam Dziewonski and Don Anderson in 1981 is still the standard Earth model
used (although other updated models now exist – e.g., IASP91, AK135, etc). The
next figure shows what this model looks like:

| [./media/image1.png](./media/image1.png) |
|------------------------------------------|


Just considering density (ρ), we may make the following observations:

-   There are major jumps at depths of: 220, 410, 670 km, as well as at the
    core-mantle boundary (CMB) and inner core boundary (ICB).

-   The density increase at the CMB is actually bigger than the density jump at
    the Earth’s surface.

-   We expect to see a density increase at depths of 410 and 670 km based on
    olivine phase changes, but why is there a jump at 220 km?

For now, let’s not worry too much more about this figure, other than to say that
seismic techniques have been used to provide us with a good constraint on
seismic wave velocity and density structure of the Earth.

**2. Mass and Moment of Inertia**
---------------------------------

*2.1 Planetary Mass*

Another important constraint on what the Earth is made of comes from its mass.
But, how do we know the Earth’s mass?

There are a couple of back of the envelope type of calculations we can do to get
within the ballpark:

Recall that from Newton’s second law:

$$
F = ma
$$

And from Newton’s law of gravitation:

$$
F = G\frac{m_{E}m}{R_{E}^{2}}
$$

Where, *mE* and *RE* are the mass and radius of the Earth respectively.

An object with mass, m, will thus experience the force:

$$
F = mg
$$

And thus,

$$
mg = G\frac{m_{E}m}{R_{E}^{2}}
$$

$$
\Longrightarrow m_{E} = \frac{R_{E}^{2}}{G}g
$$

Putting in some numbers:

| g    | = 9.8 m/s2               |
|------|--------------------------|
| *RE* | = 6371 km                |
| G    | = 6.673×10-11 m3 kg-1 s2 |

We get *mE* = 5.961×1024 kg

A current measurement gives us 5.9723×1024 kg, so our first back of the envelope
calculation doesn’t do too badly.

Another way to solve this problem is to look at orbital data. From Kepler’s law
of periods:

$$
T^{2} = \left( \frac{4\pi^{2}}{\text{Gm}} \right)r^{3}
$$

Where, in this case the mass (*m*) is given for the central body (e.g., the
earth) and the orbital period (*T*) is for a satellite orbiting the central body
at the radius *r*. Thus, we can measure the orbital period of a satellite
(artificial or a moon) without even knowing the mass of the satellite, and
determine the mass of the central planet.

We didn’t really even have a good measurement of the mass of the planets Mercury
or Venus (each of which have no moons) until we actually put spacecraft in orbit
around them.

Of course, these techniques as presented here are a bit over simplistic, but
give us a reasonable estimate of the Earth’s mass. In order to get more
sophisticated formulas we will have to treat gravity appropriately and consider
non-spherical bodies.
