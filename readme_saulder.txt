J/A+A/596/A14       Group catalogues of the local universe      (Saulder+, 2016)
================================================================================
The matter distribution in the local Universe as derived from galaxy
groups in SDSS DR12 and 2MRS.
    Saulder C., van Kampen E., Chilingarian I., Mieske S., Zeilinger W.W.
    <Astron. Astrophys. 596, A14 (2016)>
    =2016A&A...596A..14S        (SIMBAD/NED BibCode)
================================================================================
ADC_Keywords: Galaxies, nearby ; Clusters, galaxy
Keywords: galaxies: clusters: general - galaxies: distances and redshifts -
          cosmology: large-scale structure of Universe - galaxies: statistics

Abstract:
    Friends-of-friends algorithms are a common tool to detect galaxy
    groups and clusters in large survey data. In order to be as precise as
    possible, they have to be carefully calibrated using mock catalogues.

    We create an accurate and robust description of the matter
    distribution in the local Universe using the most up-to-date available
    data. This will provide the input for a specific cosmological test
    planned as follow-up to this work, and will be useful for general
    extragalactic and cosmological research.

    We create a set of galaxy group catalogues based on the 2MRS (Huchra
    et al., 2012, Cat. J/ApJS/199/26) and SDSS DR12 galaxy samples using a
    friends-of-friends based group finder algorithm. The algorithm is
    carefully calibrated and optimised on a new set of wide-angle mock
    catalogues from the Millennium simulation, in order to provide
    accurate total mass estimates of the galaxy groups taking into account
    the relevant observational biases in 2MRS and SDSS.

    We provide four different catalogues: (i) a 2MRS based group
    catalogue; (ii) a SDSS DR12 based group catalogue reaching out to a
    redshift z=0.11 with stellar mass estimates for 70% of the galaxies;
    (iii) a catalogue providing additional fundamental plane distances for
    all groups of the SDSS catalogue that host elliptical galaxies; (iv) a
    catalogue of the mass distribution in the local Universe based on a
    combination of our 2MRS and SDSS catalogues.

    While motivated by a specific cosmological test, three of the four
    catalogues that we produced are well suited to act as reference
    databases for a variety of extragalactic and cosmological science
    cases. Our catalogue of fundamental plane distances for SDSS groups
    provides further added value to this paper.

Description:
    This set of catalogues contains a 2MRS based group catalogue and a
    SDSS based group catalogue with comprehensive data on the group's
    parameters and the galaxies used to obtain these catalogues. The 2MRS
    group catalogue is the file grlist_2.dat corresponding to Table A.1 in
    the paper.
    The list of 2MRS galaxies used for this catalogue can be found in the
    file galist_2.dat, which corresponds to Table A.6 in the paper.
    The SDSS group catalogue is the file grlist_s.dat corresponding to
    Table A.2 in the paper.
    The list of SDSS galaxies used for this catalogue can be found in the
    file galist_s.dat, which corresponds to Table A.7 in the paper. It
    also contains fundamental plane distance catalogues based on SDSS
    data. They are presented for three different Lambda-CDM cosmologies
    (the cosmology of the Millennium simulation with Omega_L=0.75,
    Omega_M=0.25, and H0=73, the cosmology based on recent
    Planck-observations with Omega_L=0.685, Omega_M=0.315, and H0=67.3,
    and a "simple" cosmology with Omega_L=0.7, Omega_M=0.3, and H0=70) and
    cover the redshift range of our SDSS group catalogue, but also reach
    beyond it for individual galaxies.
    The files fpd_gr_m.dat, fpd_gr_p.dat, and fpd_gr_s.dat provide the
    fundamental plane distances to all groups hosting early-type galaxies
    and correspond to Table A.3 in the paper.
    We also provide lists of the group based fundamental plane distances
    for all galaxies in these group in the files fpd_ga_m.dat,
    fpd_ga_p.dat, and fpd_ga_s.dat corresponding to Table A.4 in the
    paper.
    All galaxies used in the fundamental plane calibrations, but beyond
    the limits of our SDSS group catalogue, have their fundamental plane
    distances listed in the files fpd_be_m.dat, fpd_be_p.dat, and
    fpd_be_s.dat, which correspond to Table A.5 in the paper.
    Additionally, a catalogue of finite infinity regions (for timescape
    cosmology) is also available. It was derived from the 2MRS and SDSS
    group catalogue for two slightly different approximations for a future
    observational test of timescape cosmology.
    The finite infinity regions are provided in the files fireg_ba.dat and
    fireg_fm.dat corresponding to Table A.8 in the paper.

File Summary:
--------------------------------------------------------------------------------
 FileName      Lrecl  Records   Explanations
--------------------------------------------------------------------------------
ReadMe            80        .   This file
grlist_2.dat     168    31506   List of groups and their parameters detected
                                 in 2MRS (Table A.1)
grlist_s.dat     168   229893   List of groups and their parameters detected
                                 in SDSS DR12 (Table A.2)
galist_2.dat      84    43425   List of 2MRS galaxies used, as well as their
                                 IDs and coordinates (Table A.6)
galist_s.dat      84   402439   List of SDSS galaxies used, as well as their
                                 IDs and coordinates (Table A.7)
fpd_gr_m.dat     188    35849   Fundamental plane distances to groups in SDSS
                                 using the cosmology of the Millennium
                                 simulation (Table A.3)
fpd_gr_p.dat     188    35849   Fundamental plane distances to groups in SDSS
                                 using the cosmology of the recent Planck
                                 observations (Table A.3)
fpd_gr_s.dat     188    35849   Fundamental plane distances to groups in SDSS
                                 using a "simple" cosmology (Table A.3)
fpd_ga_m.dat     138   145359   Fundamental plane distances to galaxies in the
                                 group catalogue using the cosmology of the
                                 Millennium simulation (Table A.4)
fpd_ga_p.dat     138   145359   Fundamental plane distances to galaxies in the
                                 group catalogue using the cosmology of the
                                 recent Planck observations (Table A.4)
fpd_ga_s.dat     138   145359   Fundamental plane distances to galaxies in the
                                 group catalogue using a "simple" cosmology
                                 (Table A.4)
fpd_be_m.dat     118    69668   Fundamental plane distances to galaxies in SDSS
                                 beyond the limits of our group catalogue using
                                 the cosmology of the Millennium simulation
                                 (Table A.5)
fpd_be_p.dat     118    69683   Fundamental plane distances to galaxies in SDSS
                                 beyond the limits of our group catalogue using
                                 the cosmology of the recent Planck observations
                                 (Table A.5)
fpd_be_s.dat     118    69679   Fundamental plane distances to galaxies in SDSS
                                 beyond the limits of our group catalogue using
                                 a "simple" cosmology (Table A.5)
fireg_ba.dat      70   171801   List of finite infinity regions from detected
                                 groups (Table A.8)
fireg_fm.dat      70   154406   List of finite infinity regions rescaled to the
                                 full mass of the cosmology (Table A.8)
--------------------------------------------------------------------------------

See also:
 J/A+A/514/A102   : SDSS DR7 groups of galaxies (Tago+, 2010)
 J/MNRAS/418/1409 : Compact groups of galaxies in SDSS DR7 (Mendel+, 2011)
 J/A+A/540/A106   : SDSS-DR8 groups and clusters of galaxies (Tempel+, 2012)
 J/MNRAS/426/296  : Compact Groups of galaxies from 2MASX (Diaz-Gimenez+, 2012)
 J/A+A/566/A1     : SDSS galaxies Flux- and volume-limited groups (Tempel+ 2014)
 J/A+A/578/A61    : Galaxy groups in the 2M++ (Diaz-Gimenez+, 2015)
 J/AJ/149/171     : 2MASS galaxy group catalog (Tully, 2015)
 J/A+A/588/A14    : Friends-of-friends galaxy group finder (Tempel+, 2016)
 J/A+A/590/A29    : Multi-frequency galaxy group catalogue (Poudel+, 2016)
 J/MNRAS/412/2498 : Galaxy groups & clouds in local universe (Makarov+, 2016)

 J/ApJS/199/26        : The 2MASS Redshift Survey (2MRS) (Huchra+, 2012)
 http://sdss.org/dr12 : SDSS DR12 Home Page

Byte-by-byte Description of file: grlist_2.dat grlist_s.dat
--------------------------------------------------------------------------------
   Bytes Format Units    Label    Explanations
--------------------------------------------------------------------------------
   1-  8  I8    ---      iGrID    Internal 2MRS or SDSS group ID
   9- 22  F14.8 deg      RAdeg    Right ascension (J2000.0) of the group centre
  23- 36  F14.8 deg      DEdeg    Declination (J2000.0) of the group centre
  37- 46  F10.7 ---      z        Redshift of the group centre (CMB-corrected)
  47- 56  F10.5 [Lsun]   logLtot  logarithm of the total (extrapolated)
                                   luminosity of the group (1)
  57- 66  F10.5 [Lsun] e_logLtot  Uncertainty of total luminosity
  67- 76  F10.5 [Lsun]   logLobs  logarithm of the observed luminosity
                                   of the group (1)
  77- 86  F10.5 [Msun]   logMtot  logarithm of the total mass of the group
  87- 96  F10.5 [Msun] e_logMtot  Uncertainty of the total mass
  97-106  F10.5 [Msun]   logMstar ?=-99.99 logarithm of the minimal stellar
                                   mass (2)
 107-112  I6    ---      NMstar   Number of galaxies in the group for which
                                   stellar masses are available
 113-122  F10.4 [Msun]   logMdyn  ?=0 logarithm of the dynamical mass of the
                                   group (3)
 123-132  F10.4 km/s     sigma    ?=0 Velocity dispersion of the group (3)
 133-142  F10.4 kpc      Rad      ?=0 Radius of the group (3)
 143-152  F10.6 deg      angRad   ?=0 Angular radius of the group (3)
 153-162  F10.4 Mpc      DL       Luminosity distance to the group
                                   (redshift based)
 163-168  I6    ---      Ntot     Total number of galaxies in the group
--------------------------------------------------------------------------------
Note (1): Luminosity in Ks band for 2MRS, r band for SDSS groups.
Note (2): If no stellar mass is available for any galaxy in the group, the
          value will be set to -99.99.
Note (3): Only available for groups hosting more than one galaxy.
--------------------------------------------------------------------------------

Byte-by-byte Description of file: galist_2.dat galist_s.dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label     Explanations
--------------------------------------------------------------------------------
   1-  8  I8    ---     iGalID    Internal 2MRS or SDSS galaxy ID
   9- 16  I8    ---     iGrID     Internal 2MRS or SDSS group ID
  17- 36  A20   ---     Name      2MASS name (HHMMSSss+DDMMSSs) or
                                   DR12 Object ID number
  37- 50  F14.8 deg     RAdeg     Right ascension (J2000.0)
  51- 64  F14.8 deg     DEdeg     Declination (J2000.0)
  65- 74  F10.7 ---     z         Redshift (CMB-corrected)
  75- 84  F10.5 [Msun]  logMstar  ?=-99.99 logarithm of the stellar mass (1)
--------------------------------------------------------------------------------
Note (1): If no stellar mass is available for this galaxy, the value will be
          set to -99.99.
--------------------------------------------------------------------------------

Byte-by-byte Description of file: fpd_gr_m.dat fpd_gr_p.dat fpd_gr_s.dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label    Explanations
--------------------------------------------------------------------------------
   1-  8  I8    ---     iGrID    Internal SDSS group ID
   9- 22  F14.8 deg     RAdeg    Right ascension (J2000.0) of the group centre
  23- 36  F14.8 deg     DEdeg    Declination (J2000.0) of the group centre
  37- 46  F10.7 ---     z        Redshift of the group centre (CMB-corrected)
  47- 56  F10.7 ---   e_z        Uncertainty of the group redshift
  57- 66  F10.4 Mpc     DAfp     Angular diameter distance derived from the
                                  fundamental plane
  67- 76  F10.4 Mpc   e_DAfp     Uncertainty of the angular diameter distance
  77- 86  F10.4 Mpc     DCfp     Co-moving distance derived from the
                                  fundamental plane
  87- 96  F10.4 Mpc   e_DCfp     Uncertainty of the co-moving distance
  97-106  F10.4 Mpc     DLfp     Luminosity distance derived from the
                                  fundamental plane
 107-116  F10.4 Mpc   e_DLfp     Uncertainty of the luminosity distance
 117-126  F10.4 Mpc     DAz      Angular diameter distance derived from the
                                  redshift
 127-136  F10.4 Mpc   e_DAz      Uncertainty of the angular diameter distance
 137-146  F10.4 Mpc     DCz      Co-moving distance derived from the redshift
 147-156  F10.4 Mpc   e_DCz      Uncertainty of the co-moving distance
 157-166  F10.4 Mpc     DLz      Luminosity distance derived from the redshift
 167-176  F10.4 Mpc   e_DLz      Uncertainty of the luminosity distance
 177-182  I6    ---     Netg     Number of early-type galaxies in group
 183-188  I6    ---     Ntot     Total number of galaxies in group
--------------------------------------------------------------------------------

Byte-by-byte Description of file: fpd_ga_m.dat fpd_ga_p.dat fpd_ga_s.dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label     Explanations
--------------------------------------------------------------------------------
   1-  8  I8    ---     iGalID    Internal SDSS galaxy ID
   9- 16  I8    ---     iGrID     Internal SDSS group ID
  17- 36  I20   ---     ObjID     SDSS DR12 Object ID number
  37- 50  F14.8 deg     RAdeg     Right ascension (J2000.0)
  51- 64  F14.8 deg     DEdeg     Declination (J2000.0)
  65- 74  F10.7 ---     z         Group redshift (CMB-corrected)
  75- 84  F10.4 Mpc     DL        Luminosity distance derived from the
                                   fundamental plane
  85- 94  F10.4 Mpc   e_DL        Uncertainty of the Luminosity distance
  95-104  F10.4 Mpc     DC        Co-moving distance derived from the
                                   fundamental plane
 105-114  F10.4 Mpc   e_DC        Uncertainty of the Co-moving distance
 115-124  F10.4 Mpc     DA        Angular diameter distance derived from the
                                  fundamental plane
 125-134  F10.4 Mpc   e_DA        Uncertainty of the Angular diameter distance
 135-138  I4    ---     etgflag   [0/1] flag if early-type galaxy
                                   (1=true, 0=false)
--------------------------------------------------------------------------------

Byte-by-byte Description of file: fpd_be_m.dat fpd_be_p.dat fpd_be_s.dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label     Explanations
--------------------------------------------------------------------------------
   1- 20  I20   ---     ObjID     SDSS DR12 Object ID number
  21- 34  F14.8 deg     RAdeg     Right ascension (J2000.0)
  35- 48  F14.8 deg     DEdeg     Declination (J2000.0)
  49- 58  F10.7 ---     z         Redshift (CMB-corrected)
  59- 68  F10.4 Mpc     DL        Luminosity distance derived from the
                                   fundamental plane
  69- 78  F10.4 Mpc   e_DL        Uncertainty of the luminosity distance
  79- 88  F10.4 Mpc     DC        Co-moving distance derived from the
                                   fundamental plane
  89- 98  F10.4 Mpc   e_DC        Uncertainty of the co-moving distance
  99-108  F10.4 Mpc     DA        Angular diameter distance derived from the
                                   fundamental plane
 109-118  F10.4 Mpc   e_DA        Uncertainty of the angular diameter
--------------------------------------------------------------------------------

Byte-by-byte Description of file: fireg_ba.dat fireg_fm.dat
--------------------------------------------------------------------------------
   Bytes Format Units    Label   Explanations
--------------------------------------------------------------------------------
   1- 10  F10.3 Mpc      Xpos    x-coordinate of the centre of a finite
                                  infinity region
  11- 20  F10.3 Mpc      Ypos    y-coordinate of the centre of a finite
                                 infinity region
  21- 30  F10.3 Mpc      Zpos    z-coordinate of the centre of a finite
                                  infinity region
  31- 40  F10.5 [Msun]   logM    logarithm of the mass within the finite
                                  infinity region
  41- 50  F10.5 [Msun] e_logM    Uncertainty of the mass estimate
  51- 60  F10.5 Mpc      Rad     Radius of the finite infinity region
  61- 70  F10.5 Mpc    e_Rad     Uncertainty of the radius of the finite
                                  infinity region
--------------------------------------------------------------------------------

Acknowledgements:
    Christoph Saulder, christoph.saulder(at)equinoxomega.net

================================================================================
(End)  C. Saulder [University of Vienna, Austria], P. Vannier [CDS]  05-Aug-2016
