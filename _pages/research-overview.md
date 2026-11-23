---
layout: page
title: Research Overview
permalink: /research/
description: Turning spatially resolved spectra into maps of galaxy motion and physical conditions.
nav: true
nav_order: 1
---

<div class="research-overview">
  <div class="research-introduction">
    <p class="research-eyebrow">From light to spatial insight</p>
    <p>Galaxies are made up of stars, gas, dust, and dark matter. Images taken through different filters show us how galaxies appear at different wavelengths of light, from blue to red. Spectroscopy takes us a step further, revealing how stars and gas in galaxies move, as well as the chemical composition, temperature, and density of that gas. 
    </p>
    <p>
    My research uses integral field spectroscopy (IFS), a technique that combines the power of imaging and spectroscopy. Rather than capturing a single spectrum of a galaxy, IFS collects a spectrum of light at every spatial pixel in an image. This creates a three-dimensional dataset, with two spatial dimensions and a third dimension containing wavelength information. By analyzing these spectra, I can construct detailed maps of how gas and stars move, their chemical properties, and the physical conditions across a galaxy, revealing how these characteristics vary from one region to another.
    </p>
  </div>

  <section class="research-study" aria-labelledby="research-looking-ahead">
    <div class="research-study__heading">
      <h2 id="research-looking-ahead">Looking ahead</h2>
    </div>
    <p>
      My forthcoming work with the <strong>GARDEN</strong> and <strong>MEADOW</strong> surveys examines gas kinematics in distant galaxies as they were <strong>7–13 billion years ago</strong>. Below are examples of peer-reviewed research I led of galaxies closer to our own Milky Way galaxy. These works showcase how I turn complex, high-dimensional data sets into meaningful information.
    </p>
  </section>

  <section class="research-study" aria-labelledby="research-kinematics">
    <div class="research-study__heading">
      <h2 id="research-kinematics">Mapping how galaxies move</h2>
    </div>
    <p>
    Light carries information about how gas and stars move within galaxies. When gas or stars move toward or away from us, their characteristic spectral features shift to shorter or longer wavelengths, a phenomenon known as the Doppler effect. The shapes and widths of these features also reveal the range of velocities present, helping us distinguish between ordered rotation and more chaotic motions. Quantifying the motions of stars and gas is known as kinematics. By modeling these spectral features across a galaxy, I construct spatial maps of the kineamtics of both gas and stellar. These maps allow me to trace the overall rotation sense of rotation in galaxies and identify regions of complex or turbulent motion.
    </p>
    <p>
      In the nearby elliptical galaxy, IC 1459, I analyzed observations from the MUSE integral field unit on the Very Large Telescope to map the brightness, velocity, and velocity dispersion of gas and stars in the galaxy. The maps below reveal a complex, filamentary gas structure, with some regions moving toward us (regions colored blue) and others moving away (regions colored red). Importantly, the gas rotates in the opposite direction from the stars in the central region of the galaxy, suggesting that the gas and stars have different origins and that some gas was acquired later from the surrounding environment.
    </p>
    <figure class="research-figure research-figure--feature">
      <a href="{{ '/assets/img/research/ic1459_figure3.png' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open full-resolution IC 1459 kinematic maps in a new tab">
        <img src="{{ '/assets/img/research/ic1459_figure3.png' | relative_url }}" alt="Multi-panel spatial maps of IC 1459 showing emission-line intensity, gas velocity and dispersion for six spectral lines, alongside maps of stellar kinematics." width="1891" height="2047" loading="lazy" decoding="async">
      </a>
      <figcaption><strong>Figure 3 · IC 1459.</strong> From left to right: maps of gas emission strength, line-of-sight velocity, and velocity dispersion for different spectral features; the rightmost column maps stellar motion. Each image is a different property extracted from the same spatially resolved spectral dataset. <span class="research-figure__hint">Select the figure to view it full size.</span></figcaption>
    </figure>
    <figure class="research-figure research-figure--feature">
      <a href="{{ '/assets/img/research/ic1459_context_overview.png' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open full-resolution Figure 4, showing IC 1459 from its group environment to its ionized gas, in a new tab">
        <img src="{{ '/assets/img/research/ic1459_context_overview.png' | relative_url }}" alt="Four-panel view zooming into IC 1459: neutral hydrogen gas in the surrounding galaxy group, a deep optical image, a hydrogen-alpha plus nitrogen emission image, and a detailed nitrogen emission-line intensity map." width="1992" height="514" loading="lazy" decoding="async">
      </a>
      <figcaption><strong>Figure 4 · IC 1459 in its environment.</strong> These images zoom progressively inward, connecting gas in the surrounding galaxy group to the detailed structure revealed by spectroscopy. From left to right: the group’s neutral hydrogen (H I) map from <strong>Saponara et al. (2018)</strong>, a deep optical image from <strong>Malin (1985)</strong>, an H&alpha; + [N II] image of IC 1459 (about 1.34 arcminutes across) from <strong>Goudfrooij et al. (1990a)</strong>, and our spatially resolved [N II] emission-line map of the central 30 arcseconds. The final panel traces the ionized gas whose motion is mapped in Figure 3 above. <span class="research-figure__hint">Select the figure to view it full size.</span></figcaption>
    </figure>
    <p class="research-study__publication"><span>Peer-reviewed publication · 2021</span> <a href="https://doi.org/10.1093/mnras/stab1137" target="_blank" rel="noopener noreferrer">Deciphering the origin of ionized gas in IC 1459 with VLT/MUSE <span aria-hidden="true">↗</span></a></p>
  </section>

  <section class="research-study" aria-labelledby="research-chemistry">
    <div class="research-study__heading">
      <h2 id="research-chemistry">Reading the signatures in light</h2>
    </div>
    <p>
      Every element leaves recognizable features in a spectrum. By comparing the strengths of emission lines from elements such as hydrogen, nitrogen, oxygen, and sulfur, one can identify the physical processes energizing gas in different parts of a galaxy. Some regions are powered by young stars, while others reflect activity around a central black hole, shocks, or older stellar populations. These patterns can be hidden when a whole galaxy is represented by a single spectrum.
    </p>
    <p>
    In a study combining optical integral field spectroscopy from the MaNGA survey with radio observations from LOFAR, I examined a statistical sample of galaxies hosting radio-detected active galactic nuclei (AGN) and compared them with a control sample of galaxies matched in stellar mass, redshift, morphology, and inclination, but without active nuclei. Traditionally, astronomers use diagnostic diagrams based on spectral emission lines to classify galaxies according to their dominant source of ionization. However, a single classification can oversimplify the complex processes occurring within a galaxy. In this work, I combined multiple spectral diagnostics to classify the dominant ionization mechanism at each spatial pixel, constructing maps that reveal where different sources of ionization are located.
    </p>
    <p>
    The figure below illustrates the power of integral field spectroscopy when studying the internal properties of galaxies. The AGN host galaxy (left) and its matched control galaxy (right) are remarkably similar in their images. However, their spatially resolved maps reveal striking differences. In the AGN host, star formation is distributed in a ring-like structure across the galaxy, whereas the control galaxy exhibits a strong central concentration of star formation. These spatial patterns would be difficult to distinguish from a single spectrum or galaxy-wide measurement. IFS allows us to determine not only how much star formation is occurring, but where within a galaxy it is taking place, providing a more complete picture of galaxy evolution and a way to investigate the potential influence of central black holes on their host galaxies.
    </p>
    <div class="research-figure-grid">
      <figure class="research-figure">
        <a href="{{ '/assets/img/research/manga_lofar_figure8.png' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open full-resolution emission-line diagnostic diagrams and ionization map in a new tab">
          <img src="{{ '/assets/img/research/manga_lofar_figure8.png' | relative_url }}" alt="Four-panel visualization showing nitrogen and sulfur emission-line diagnostic scatter plots, a WHAN diagram, and the resulting spatial classification map of galaxy 8978-9101." width="2048" height="1689" loading="lazy" decoding="async">
        </a>
        <figcaption><strong>Figure 8 · From signatures to classes.</strong> Ratios of spectral lines and the strength of hydrogen emission are combined to classify each spatial pixel. The resulting map reveals distinct regions of star formation and other ionization mechanisms.</figcaption>
      </figure>
      <figure class="research-figure">
        <a href="{{ '/assets/img/research/manga_lofar_figure9_selected.png' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open full-resolution galaxy and control comparison maps in a new tab">
          <img src="{{ '/assets/img/research/manga_lofar_figure9_selected.png' | relative_url }}" alt="Selected panels of Figure 9 comparing a radio-active galaxy and its control: optical images, spatial ionization classification maps and star formation rate surface-density maps." width="864" height="1125" loading="lazy" decoding="async">
        </a>
        <figcaption><strong>Figure 9 · Comparing spatial patterns.</strong> Selected panels compare a radio-active galaxy with a matched inactive control. Their classification and star-formation maps show how physical properties vary across each galaxy.</figcaption>
      </figure>
    </div>
    <p>
      Across the wider sample, we found that radio-active galaxies and their inactive counterparts have broadly similar star-formation histories. The results suggest that current AGN activity does not, on its own, explain why star formation has slowed in these galaxies.
    </p>
    <p class="research-study__publication"><span>Peer-reviewed publication · 2022</span> <a href="https://doi.org/10.1051/0004-6361/202142215" target="_blank" rel="noopener noreferrer">Star formation and AGN feedback in the local Universe: Combining LOFAR and MaNGA <span aria-hidden="true">↗</span></a></p>
  </section>
</div>
