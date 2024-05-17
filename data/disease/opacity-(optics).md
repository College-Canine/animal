{{Short description|Property of an object or substance that is impervious to light}}
{{redirect|Opacity}}
{{Refimprove|date=February 2010}}
[[File:Opacity Translucency Transparency.svg|thumb|250px|right|Comparisons of 1. opacity, 2. translucency, and 3. transparency; behind each panel is a star.]]
'''Opacity''' is the measure of impenetrability to [[electromagnetic radiation|electromagnetic]] or other kinds of [[radiation]], especially visible [[light]].  In [[radiative transfer]], it describes the absorption and scattering of radiation in a [[transmission medium|medium]], such as a [[plasma (physics)|plasma]], [[dielectric]], [[radiation shield|shielding material]], glass, etc. An '''opaque''' object is neither [[Transparency (optics)|transparent]] (allowing all light to pass through) nor [[translucent]] (allowing some light to pass through). When light strikes an interface between two substances, in general some may be reflected, some absorbed, some scattered, and the rest transmitted (also see [[refraction]]). Reflection can be [[diffuse reflection|diffuse]], for example light reflecting off a white wall, or [[specular reflection|specular]], for example light reflecting off a mirror. An opaque substance transmits no light, and therefore reflects, scatters, or absorbs all of it. Other categories of visual appearance, related to the perception of regular or diffuse reflection and transmission of light, have been organized under the concept of [[Cesia (visual appearance)|cesia]] in an order system with three variables, including opacity, transparency and translucency among the involved aspects. Both [[mirror]]s and [[carbon black]] are opaque. Opacity depends on the [[frequency]] of the light being considered. For instance, some kinds of [[glass]], while transparent in the [[visible light|visual range]], are largely opaque to [[ultraviolet]] light. More extreme frequency-dependence is visible in the [[absorption line]]s of cold [[gas]]es. Opacity can be quantified in many ways; for example, see the article [[mathematical descriptions of opacity]].

Different processes can lead to opacity including [[absorption (electromagnetic radiation)|absorption]], [[reflection (physics)|reflection]], and [[light scattering|scattering]].
==Etymology==
Late Middle English opake, from Latin opacus 'darkened'. The current spelling (rare before the 19th century) has been influenced by the French form.

==Radiopacity==
{{Main|Radiodensity}}
''Radiopacity'' is preferentially used to describe opacity of [[X-rays]]. In modern medicine, radiodense substances are those that will not allow X-rays or similar radiation to pass. [[Radiography|Radiographic imaging]] has been revolutionized by radiodense [[contrast medium|contrast media]], which can be passed through the bloodstream, the [[gastrointestinal tract]], or into the cerebral spinal fluid and utilized to highlight CT scan or X-ray images. Radiopacity is one of the key considerations in the design of various devices such as guidewires or [[stent]]s that are used during [[radiology|radiological]] intervention. The radiopacity of a given endovascular device is important since it allows the device to be tracked during the interventional procedure.

==Quantitative definition==
{{See also|Extinction (astronomy)|attenuation coefficient}}

The words "opacity" and "opaque" are often used as colloquial terms for objects or media with the properties described above. However, there is also a specific, quantitative definition of "opacity", used in astronomy, plasma physics, and other fields, given here.

In this use, "opacity" is another term for the [[mass attenuation coefficient]] (or, depending on context, [[mass absorption coefficient]], the difference is described [[Absorption coefficient#Attenuation versus absorption|here]]) <math>\kappa_\nu</math> at a particular frequency <math>\nu</math> of electromagnetic radiation.

More specifically, if a beam of light with frequency <math>\nu</math> travels through a medium with opacity <math>\kappa_\nu</math> and mass density <math>\rho</math>, both constant, then the intensity will be reduced with distance ''x'' according to the formula
<math display="block">I(x) = I_0 e^{-\kappa_\nu \rho x}</math>
where
* ''x'' is the distance the light has traveled through the medium
* <math>I(x)</math> is the intensity of light remaining at distance ''x''
* <math>I_0</math> is the initial intensity of light, at <math>x = 0</math>

For a given medium at a given frequency, the opacity has a numerical value that may range between 0 and infinity, with units of length<sup>2</sup>/mass.

Opacity in air pollution work refers to the percentage of light blocked instead of the attenuation coefficient (aka extinction coefficient) and varies from 0% light blocked to 100% light blocked:

<math display="block">\text{Opacity} = 100\% \left(1-\frac{I(x)}{I_0} \right)</math>

===Planck and Rosseland opacities===
It is customary to define the average opacity, calculated using a certain weighting scheme. '''Planck opacity''' (also known as Planck-Mean-Absorption-Coefficient<ref>Modest, Radiative Heat Transfer, {{ISBN|978-0-12386944-9}}</ref>) uses the normalized [[Planck's law|Planck black-body radiation energy density distribution]], <math> B_{\nu}(T)</math>, as the weighting function, and averages <math>\kappa_\nu</math> directly:
<math display="block">\kappa_{Pl}={\int_0^\infty \kappa_\nu B_\nu(T) d\nu \over   \int_0^\infty B_\nu(T) d\nu }=\left( { \pi \over \sigma T^4}\right) \int_0^\infty \kappa_\nu B_\nu(T) d\nu ,</math>
where <math>\sigma</math> is the [[Stefan–Boltzmann constant]].

'''Rosseland opacity''' (after [[Svein Rosseland]]), on the other hand, uses a temperature derivative of the [[Planck's law of black body radiation|Planck distribution]], <math>u(\nu, T)=\partial B_\nu(T)/\partial T</math>, as the weighting function, and averages <math>\kappa_\nu^{-1}</math>,
<math display="block">\frac{1}{\kappa} = \frac{\int_0^{\infty} \kappa_{\nu}^{-1} u(\nu, T) d\nu }{\int_0^{\infty} u(\nu,T) d\nu}.</math>
The photon mean free path is  <math>\lambda_\nu = (\kappa_\nu \rho)^{-1}</math>. The Rosseland opacity is derived in the diffusion approximation to the radiative transport equation. It is valid whenever the radiation field is isotropic over distances comparable to or less than a radiation mean free path, such as in local thermal equilibrium. In practice, the mean opacity for [[Thomson scattering|Thomson electron scattering]] is:
<math display="block">\kappa_{\rm es} = 0.20(1+X) \,\mathrm{cm^2 \, g^{-1}}</math>
where <math> X </math> is the hydrogen mass fraction. For [[Bremsstrahlung|nonrelativistic thermal bremsstrahlung]], or free-free transitions, assuming solar [[metallicity]], it is:<ref>Stuart L. Shapiro and [[Saul Teukolsky|Saul A. Teukolsky]], "Black Holes, White Dwarfs, and Neutron Stars" 1983, {{ISBN|0-471-87317-9}}.</ref>
<math display="block">\kappa_{\rm ff}(\rho, T) = 0.64 \times 10^{23} (\rho[ {\rm g}~ {\rm\, cm}^{-3}])(T[{\rm K}])^{-7/2} {\rm\, cm}^2 {\rm\, g}^{-1}.</math>
The Rosseland mean [[attenuation coefficient]] is:<ref>George B. Rybicki and [[Alan Lightman|Alan P. Lightman]], "[https://books.google.com/books?id=LtdEjNABMlsC&q=%22Rosseland+mean+attenuation+coefficient%22 Radiative Processes in Astrophysics]" 1979 {{ISBN|0-471-04815-1}}.</ref>
<math display="block">\frac{1}{\kappa} = \frac{\int_0^{\infty} (\kappa_{\nu, {\rm es}} + \kappa_{\nu, {\rm ff}})^{-1} u(\nu, T) d\nu }{\int_0^{\infty} u(\nu,T) d\nu}.</math>

==See also==
{{wiktionary}}
* [[Absorption (electromagnetic radiation)]]
* [[Mathematical descriptions of opacity]]
* [[Molar absorptivity]]
* [[Reflection (physics)]]
* [[Gloss (optics)]]
* [[Cesia (visual appearance)]]
* [[Scattering theory]]
* [[Transparency and translucency]]
* [[Kappa mechanism]]

==References==
{{reflist}}

[[Category:Electromagnetic radiation]]
[[Category:Scattering, absorption and radiative transfer (optics)]]
[[Category:Spectroscopy]]
[[Category:Glass physics]]
[[Category:Physical properties]]
[[Category:Optics]]