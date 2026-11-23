---
layout: page
title: Research Overview
permalink: /research/
nav: true
nav_order: 1
---

<!-- Keep the page as raw HTML so Kramdown does not display closing tags as text. -->
<div class="research-overview" markdown="0">
  <div class="research-introduction">
    <p>
      Galaxies are made up of stars, gas, dust, and dark matter. Images taken through different filters show us how galaxies appear at different wavelengths of light, from blue to red. Spectroscopy takes us a step further, revealing how stars and gas in galaxies move, as well as the chemical composition, temperature, and density of that gas.
    </p>
    <p>
      My research uses integral field spectroscopy (IFS), a technique that combines the power of imaging and spectroscopy. Rather than capturing a single spectrum of a galaxy, IFS collects a spectrum of light at every spatial pixel in an image. This creates a three-dimensional dataset, with two spatial dimensions and a third dimension containing wavelength information. By analyzing these spectra, I can construct detailed maps of how gas and stars move, their chemical properties, and the physical conditions across a galaxy, revealing how these characteristics vary from one region to another.
    </p>
    <p>
      My forthcoming work with the <strong>GARDEN</strong> and <strong>MEADOW</strong> surveys examines gas kinematics in distant galaxies as they were <strong>7–13 billion years ago</strong>. Below are examples of peer-reviewed research I led on galaxies closer to our own Milky Way. These works are representative of the analyses I am performing on these distant galaxies.
    </p>
  </div>

  <section class="research-study" aria-labelledby="research-kinematics">
    <div class="research-study__heading">
      <h2 id="research-kinematics">Mapping how galaxies move</h2>
    </div>
    <p>
      Light carries information about how gas and stars move within galaxies. When gas or stars move toward or away from us, their characteristic spectral features shift to shorter or longer wavelengths, a phenomenon known as the Doppler effect. The shapes and widths of these features also reveal the range of velocities present, helping us distinguish between ordered rotation and more chaotic motions. Quantifying the motions of stars and gas is known as kinematics. By modeling these spectral features across a galaxy, I construct spatial maps of both gas and stellar kinematics. These maps allow me to trace a galaxy's overall rotation and identify regions of complex or turbulent motion.
    </p>
    <p>
      In the nearby elliptical galaxy IC 1459, I analyzed observations from the MUSE integral field unit on the Very Large Telescope to map the brightness, velocity, and velocity dispersion of gas and stars. The maps below reveal a complex, filamentary gas structure, with some regions moving toward us (shown in blue) and others moving away (shown in red). Importantly, the gas rotates in the opposite direction from the stars in the central region of the galaxy, suggesting that the gas and stars have different origins and that some gas was acquired later from the surrounding environment.
    </p>
    <figure class="research-figure research-figure--feature">
      <a href="{{ '/assets/img/research/ic1459_figure3.png' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open full-resolution IC 1459 kinematic maps in a new tab">
        <img src="{{ '/assets/img/research/ic1459_figure3.png' | relative_url }}" alt="Multi-panel spatial maps of IC 1459 showing emission-line intensity, gas velocity and dispersion for six spectral lines, alongside maps of stellar kinematics." width="1891" height="2047" loading="lazy" decoding="async">
      </a>
      <figcaption><strong>Figure 1:</strong> From left to right: maps of gas emission strength, line-of-sight velocity, and velocity dispersion for different spectral features; the rightmost column maps stellar motion. We make these maps using emission lines from elements including hydrogen, oxygen, nitrogen, and sulfur.</figcaption>
    </figure>
    <figure class="research-figure research-figure--feature">
      <a href="{{ '/assets/img/research/ic1459_context_overview.png' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open full-resolution IC 1459 environment figure in a new tab">
        <img src="{{ '/assets/img/research/ic1459_context_overview.png' | relative_url }}" alt="Four-panel view zooming into IC 1459: neutral hydrogen gas in the surrounding galaxy group, a deep optical image, a hydrogen-alpha plus nitrogen emission image, and a detailed nitrogen emission-line intensity map." width="1992" height="514" loading="lazy" decoding="async">
      </a>
      <figcaption><strong>Figure 2:</strong> These images zoom progressively inward, connecting gas in the surrounding IC 1459 galaxy group to the detailed internal structure revealed by IFS. From left to right: the group's neutral hydrogen (H I) map from Saponara et al. (2018), a deep optical image from Malin (1985), an H&alpha; + [N II] image of IC 1459 (about 1.34 arcminutes across) from Goudfrooij et al. (1990a), and our spatially resolved [N II] emission-line map of the central 30 arcseconds. The final panel traces the ionized gas whose motion is mapped in Figure 1 above.</figcaption>
    </figure>
    <p class="research-study__publication"><a href="https://doi.org/10.1093/mnras/stab1137" target="_blank" rel="noopener noreferrer">Deciphering the origin of ionized gas in IC 1459 with VLT/MUSE <span aria-hidden="true">↗</span></a></p>
  </section>

  <section class="research-study" aria-labelledby="research-chemistry">
    <div class="research-study__heading">
      <h2 id="research-chemistry">Mapping how gas is ionized and how star formation varies across galaxies</h2>
    </div>
    <p>
      Every element leaves recognizable features in a spectrum. By comparing the strengths of emission lines from elements such as hydrogen, nitrogen, oxygen, and sulfur, we can identify what is ionizing gas in different parts of a galaxy. Some regions are ionized by young stars, while others reflect activity around a central black hole, shocks, or older stellar populations. These differences can be hidden when a whole galaxy is represented by a single spectrum.
    </p>
    <p>
      In a study combining optical IFS observations from the MaNGA survey with radio observations from LOFAR, I examined a statistical sample of galaxies hosting radio-detected active galactic nuclei (AGN) and compared them with a control sample matched in stellar mass, redshift, morphology, and inclination, but without active nuclei. Astronomers traditionally use diagnostic diagrams based on emission-line ratios to classify galaxies by their dominant source of ionization. Rather than assign one classification to an entire galaxy, I combined multiple diagnostic diagrams to determine the dominant ionization source in each spatial pixel and map where different sources occur.
    </p>
    <p>
      A key goal was to find the regions where young stars are ionizing the gas and measure star formation specifically in those regions. We could calculate a star formation rate from the hydrogen emission across an entire galaxy, but some of that emission is powered by an AGN or other sources rather than by newly formed stars. To avoid counting that emission as star formation, we measured star formation rates only in pixels classified as star-forming or composite (where star formation is expected to contribute), excluding regions dominated by AGN activity or other non-star-forming ionization sources. This gave us a more meaningful way to compare star formation in galaxies with and without active nuclei.
    </p>
    <div class="research-figure-grid">
      <figure class="research-figure">
        <a href="{{ '/assets/img/research/manga_lofar_figure8.png' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open full-resolution emission-line diagnostic diagrams and ionization map in a new tab">
          <img src="{{ '/assets/img/research/manga_lofar_figure8.png' | relative_url }}" alt="Four-panel visualization showing nitrogen and sulfur emission-line diagnostic scatter plots, a WHAN diagram, and the resulting spatial classification map of galaxy 8978-9101." width="2048" height="1689" loading="lazy" decoding="async">
        </a>
        <figcaption><strong>Figure 3:</strong> Ratios of nitrogen, sulfur, and oxygen emission lines to hydrogen emission are combined to classify the dominant source of ionization in each spatial pixel. The resulting map distinguishes regions associated with young stars, older stars, and AGN-like ionization.</figcaption>
      </figure>
      <figure class="research-figure">
        <a href="{{ '/assets/img/research/manga_lofar_figure9_selected.png' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open full-resolution galaxy and control comparison maps in a new tab">
          <img src="{{ '/assets/img/research/manga_lofar_figure9_selected.png' | relative_url }}" alt="Selected panels of Figure 9 comparing a radio-active galaxy and its control: optical images, spatial ionization classification maps and star formation rate surface-density maps." width="864" height="1125" loading="lazy" decoding="async">
        </a>
        <figcaption><strong>Figure 4:</strong> An AGN host galaxy and its matched control appear similar in optical images (top), but their ionization maps (middle) and star formation rate maps (bottom) show very different spatial patterns. The star formation maps include only regions selected using the spectral classifications.</figcaption>
      </figure>
    </div>
    <p>
      Figure 4 illustrates the power of IFS. Although the AGN host galaxy (left) and its matched control (right) appear remarkably similar in their optical images, their star formation maps look very different. In the AGN host, star formation is distributed in a ring-like structure, whereas the control has a strong central concentration. A single spectrum or galaxy-wide star formation rate would miss these differences. IFS lets us see not just how much star formation is occurring, but where within a galaxy it is taking place.
    </p>
    <p>
      Across the wider sample, we found that galaxies with radio-detected AGN and their inactive counterparts have broadly similar star formation histories. Our results suggest that current AGN activity alone does not explain why star formation has slowed in these galaxies.
    </p>
    <p class="research-study__publication"><a href="https://doi.org/10.1051/0004-6361/202142215" target="_blank" rel="noopener noreferrer">Star formation and AGN feedback in the local Universe: Combining LOFAR and MaNGA <span aria-hidden="true">↗</span></a></p>
  </section>
</div>
