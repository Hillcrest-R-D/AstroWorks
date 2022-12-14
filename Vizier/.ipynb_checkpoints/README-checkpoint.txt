data obtained from http://vizier.u-strasbg.fr/viz-bin/VizieR?-source=I/239

#Table	I_239_hip_main:
#Name: I/239/hip_main
#Title: The Hipparcos Main Catalogue
#Column	_Glon	(F8.4)	Galactic longitude at Epoch=J1991.25, proper motions taken into account 	[ucd=pos.galactic.lon]
#Column	_Glat	(F8.4)	Galactic latitude at Epoch=J1991.25, proper motions taken into account 	[ucd=pos.galactic.lat]
#Column	_RAJ2000	(F11.7)	Right ascension (FK5, Equinox=J2000.0) at Epoch=J2000, proper motions taken into account 	[ucd=pos.eq.ra]
#Column	_DEJ2000	(F11.7)	Declination (FK5, Equinox=J2000.0) at Epoch=J2000, proper motions taken into account 	[ucd=pos.eq.dec]
#Column	_RAB1950	(F11.7)	Right ascension (FK4, Equinox=B1950.0) at Epoch=J1950, proper motions taken into account 	[ucd=pos.eq.ra]
#Column	_DEB1950	(F11.7)	Declination (FK4, Equinox=B1950.0) at Epoch=J1950, proper motions taken into account 	[ucd=pos.eq.dec]
#Column	_Elon2000	(F11.7)	Ecliptic longitud Equinox=J2000.0 at Epoch=J2000, proper motions taken into account 	[ucd=pos.ecliptic.lon]
#Column	_Elat2000	(F11.7)	Ecliptic latitud Equinox=J2000.0 at Epoch=J2000, proper motions taken into account 	[ucd=pos.ecliptic.lat]
#Column	_time	(F14.6)	time (JD) in TCB/barycenter	[ucd=time.epoch]
#Column	_etime	(F7.1)	time error (uncertainty and time conversion)	[ucd=stat.error;time.epoch]
#Column	HIP	(I6)	Identifier (HIP number) (H1)	[ucd=meta.id;meta.main]
#Column	Proxy	(A1)	[HT] Proximity flag (H2)	[ucd=meta.code]
#Column	RAhms	(A11)	Right ascension in h m s, ICRS (J1991.25) (H3)	[ucd=pos.eq.ra]
#Column	DEdms	(A11)	Declination in deg ' ", ICRS (J1991.25) (H4)	[ucd=pos.eq.dec]
#Column	Vmag	(F5.2)	? Magnitude in Johnson V (H5)	[ucd=phot.mag;em.opt.V]
#Column	VarFlag	(I1)	[1,3]? Coarse variability flag (H6) [NULL integer written as an empty string]	[ucd=meta.code;src.var]
#Column	r_Vmag	(A1)	[GHT] Source of magnitude (H7)	[ucd=meta.ref;pos.frame]
#Column	RAICRS	(F12.8)	? alpha, degrees (ICRS, Epoch=J1991.25) (H8)	[ucd=pos.eq.ra;meta.main]
#Column	DEICRS	(F12.8)	? delta, degrees (ICRS, Epoch=J1991.25) (H9)	[ucd=pos.eq.dec;meta.main]
#Column	AstroRef	(A1)	[*+A-Z] Reference flag for astrometry (H10)	[ucd=meta.bib]
#Column	Plx	(F7.2)	? Trigonometric parallax (H11)	[ucd=pos.parallax.trig]
#Column	pmRA	(F8.2)	*? Proper motion mu_alpha.cos(delta), ICRS(H12)	[ucd=pos.pm;pos.eq.ra]
#Column	pmDE	(F8.2)	*? Proper motion mu_delta, ICRS (H13)	[ucd=pos.pm;pos.eq.dec]
#Column	e_RAICRS	(F6.2)	*? Standard error in RA*cos(DEdeg) (H14)	[ucd=stat.error;pos.eq.ra]
#Column	e_DEICRS	(F6.2)	*? Standard error in DE (H15)	[ucd=stat.error;pos.eq.dec]
#Column	e_Plx	(F6.2)	? Standard error in Plx (H16)	[ucd=stat.error;pos.parallax]
#Column	e_pmRA	(F6.2)	? Standard error in pmRA (H17)	[ucd=stat.error;pos.pm;pos.eq.ra]
#Column	e_pmDE	(F6.2)	? Standard error in pmDE (H18)	[ucd=stat.error;pos.pm;pos.eq.dec]
#Column	DE:RA	(F5.2)	[-1/1]? Correlation, DE/RA*cos(delta) (H19)	[ucd=stat.correlation]
#Column	Plx:RA	(F5.2)	[-1/1]? Correlation, Plx/RA*cos(delta) (H20)	[ucd=stat.correlation]
#Column	Plx:DE	(F5.2)	[-1/1]? Correlation, Plx/DE (H21)	[ucd=stat.correlation]
#Column	pmRA:RA	(F5.2)	[-1/1]? Correlation, pmRA/RA*cos(delta) (H22)	[ucd=stat.correlation]
#Column	pmRA:DE	(F5.2)	[-1/1]? Correlation, pmRA/DE (H23)	[ucd=stat.correlation]
#Column	pmRA:Plx	(F5.2)	[-1/1]? Correlation, pmRA/Plx (H24)	[ucd=stat.correlation]
#Column	pmDE:RA	(F5.2)	[-1/1]? Correlation, pmDE/RA*cos(delta) (H25)	[ucd=stat.correlation]
#Column	pmDE:DE	(F5.2)	[-1/1]? Correlation, pmDE/DE (H26)	[ucd=stat.correlation]
#Column	pmDE:Plx	(F5.2)	[-1/1]? Correlation, pmDE/Plx (H27)	[ucd=stat.correlation]
#Column	pmDE:pmRA	(F5.2)	[-1/1]? Correlation, pmDE/pmRA (H28)	[ucd=stat.correlation]
#Column	F1	(I3)	? Percentage of rejected data (H29) [NULL integer written as an empty string]	[ucd=stat.value;arith.ratio]
#Column	F2	(F5.2)	? Goodness-of-fit parameter (H30)	[ucd=stat.fit.goodness]
#Column	BTmag	(F6.3)	? Mean BT magnitude (H32)	[ucd=phot.mag;em.opt.B]
#Column	e_BTmag	(F6.3)	? Standard error on BTmag (H33)	[ucd=stat.error;phot.mag]
#Column	VTmag	(F6.3)	? Mean VT magnitude (H34)	[ucd=phot.mag;em.opt.V]
#Column	e_VTmag	(F6.3)	? Standard error on VTmag (H35)	[ucd=stat.error;phot.mag]
#Column	m_BTmag	(A1)	[A-Z*-] Reference flag for BT and VTmag (H36)	[ucd=meta.code.multip]
#Column	B-V	(F6.3)	? Johnson B-V colour (H37)	[ucd=phot.color;em.opt.B;em.opt.V]
#Column	e_B-V	(F6.3)	? Standard error on B-V (H38)	[ucd=stat.error;phot.color;em.opt.B]
#Column	r_B-V	(A1)	[GT] Source of B-V from Ground or Tycho (H39)	[ucd=meta.ref;phot.color;em.opt.B]
#Column	V-I	(F5.2)	? Colour index in Cousins' system (H40)	[ucd=phot.color;em.opt.V;em.opt.I]
#Column	e_V-I	(F5.2)	? Standard error on V-I (H41)	[ucd=stat.error;phot.color;em.opt.V]
#Column	r_V-I	(A1)	[A-T] Source of V-I (H42)	[ucd=meta.ref;phot.color;em.opt.V]
#Column	CombMag	(A1)	[*] Flag for combined Vmag, B-V, V-I (H43)	[ucd=meta.code]
#Column	Hpmag	(F7.4)	? Median magnitude in Hipparcos system (H44)	[ucd=phot.mag;em.opt.V]
#Column	e_Hpmag	(F7.4)	? Standard error on Hpmag (H45)	[ucd=stat.error;phot.mag]
#Column	Hpscat	(F6.3)	? Scatter on Hpmag (H46)	[ucd=stat.error]
#Column	o_Hpmag	(I3)	? Number of observations for Hpmag (H47) [NULL integer written as an empty string]	[ucd=meta.number]
#Column	m_Hpmag	(A1)	[A-Z*-] Reference flag for Hpmag (H48)	[ucd=meta.code.multip]
#Column	Hpmax	(F5.2)	? Hpmag at maximum (5th percentile) (H49)	[ucd=stat.error]
#Column	HPmin	(F5.2)	? Hpmag at minimum (95th percentile) (H50)	[ucd=stat.error]
#Column	Period	(F7.2)	? Variability period (days) (H51)	[ucd=src.var]
#Column	HvarType	(A1)	[CDMPRU]? variability type (H52)	[ucd=meta.note]
#Column	moreVar	(A1)	[12] Additional data about variability (H53)	[ucd=meta.code]
#Column	morePhoto	(A1)	[ABC] Light curve Annex (H54)	[ucd=meta.code]
#Column	CCDM	(A10)	CCDM identifier (H55)	[ucd=meta.id.cross]
#Column	n_CCDM	(A1)	[HIM] Historical status flag (H56)	[ucd=meta.note]
#Column	Nsys	(I2)	? Number of entries with same CCDM (H57) [NULL integer written as an empty string]	[ucd=meta.number]
#Column	Ncomp	(I2)	? Number of components in this entry (H58) [NULL integer written as an empty string]	[ucd=meta.number]
#Column	MultFlag	(A1)	[CGOVX] Double/Multiple Systems flag (H59)	[ucd=meta.code]
#Column	Source	(A1)	[PFILS] Astrometric source flag (H60)	[ucd=meta.bib]
#Column	Qual	(A1)	[ABCDS] Solution quality (H61)	[ucd=meta.code.qual;stat.fit]
#Column	m_HIP	(A2)	Component identifiers (H62)	[ucd=meta.code.multip]
#Column	theta	(I3)	? Position angle between components (H63) [NULL integer written as an empty string]	[ucd=pos.posAng]
#Column	rho	(F7.3)	? Angular separation between components (H64)	[ucd=pos.angDistance]
#Column	e_rho	(F6.3)	? Standard error on rho (H65)	[ucd=stat.error]
#Column	dHp	(F5.2)	? Magnitude difference of components (H66)	[ucd=phot.mag;arith.diff]
#Column	e_dHp	(F5.2)	? Standard error on dHp (H67)	[ucd=stat.error]
#Column	Survey	(A1)	[S] Flag indicating a Survey Star (H68)	[ucd=meta.code]
#Column	Chart	(A1)	[DG] Identification Chart (H69)	[ucd=meta.id;obs.field]
#Column	Notes	(A1)	[DGPWXYZ] Existence of notes (H70)	[ucd=meta.note]
#Column	HD	(I6)	[1/359083]? HD number <III/135> (H71) [NULL integer written as an empty string]	[ucd=meta.id.cross]
#Column	BD	(A10)	Bonner DM <I/119>, <I/122> (H72)	[ucd=meta.id.cross]
#Column	CoD	(A10)	Cordoba Durchmusterung (DM) <I/114> (H73)	[ucd=meta.id.cross]
#Column	CPD	(A10)	Cape Photographic DM <I/108> (H74)	[ucd=meta.id.cross]
#Column	(V-I)red	(F5.2)	V-I used for reductions (H75)	[ucd=phot.color;em.opt.V;em.opt.I]
#Column	SpType	(a12)	Spectral type (H76)	[ucd=src.spType]
#Column	r_SpType	(A1)	[1234GKSX]? Source of spectral type (H77)	[ucd=meta.ref;pos.frame]
#Column	HIPep	(a5)	Hipparcos Epoch Photometry (Plot and List)	[ucd=meta.ref.url]
#Column	Erratum	(a7)	VizieR added column, not part of original data	[ucd=meta.ref.url]
#Column	_RA.icrs	(F12.8)	Right ascension (ICRS) at Epoch=J2000, proper motions taken into account	[ucd=pos.eq.ra]
#Column	_DE.icrs	(F12.8)	Declination (ICRS) at Epoch=J2000, proper motions taken into account	[ucd=pos.eq.dec]