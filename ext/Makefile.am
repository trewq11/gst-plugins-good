if USE_AALIB
AALIB_DIR = aalib
else
AALIB_DIR =
endif

if USE_CAIRO
CAIRO_DIR = cairo
else
CAIRO_DIR =
endif

if USE_FLAC
FLAC_DIR = flac
else
FLAC_DIR =
endif

if USE_GDK_PIXBUF
GDK_PIXBUF_DIR = gdk_pixbuf
else
GDK_PIXBUF_DIR =
endif

if USE_JACK
JACK_DIR=jack
else
JACK_DIR=
endif

if USE_JPEG
JPEG_DIR = jpeg
else
JPEG_DIR =
endif

if USE_LIBCACA
LIBCACA_DIR = libcaca
else
LIBCACA_DIR =
endif

if USE_LIBDE265
LIBDE265_DIR = libde265
else
LIBDE265_DIR =
endif

if USE_LIBDV
LIBDV_DIR = dv
else
LIBDV_DIR =
endif

if USE_LIBPNG
LIBPNG_DIR = libpng
else
LIBPNG_DIR =
endif

# if USE_MIKMOD
# MIKMOD_DIR = mikmod
# else
MIKMOD_DIR =
# endif

if USE_DV1394
DV1394_DIR = raw1394
else
DV1394_DIR =
endif

if USE_PULSE
PULSE_DIR = pulse
else
PULSE_DIR =
endif


if USE_SHOUT2
SHOUT2_DIR = shout2
else
SHOUT2_DIR =
endif

if USE_SOUP
SOUP_DIR=soup
else
SOUP_DIR=
endif

if USE_SPEEX
SPEEX_DIR = speex
else
SPEEX_DIR =
endif

if USE_TAGLIB
TAGLIB_DIR = taglib
else
TAGLIB_DIR =
endif

if USE_VPX
VPX_DIR=vpx
else
VPX_DIR=
endif

if USE_WAVPACK
WAVPACK_DIR=wavpack
else
WAVPACK_DIR=
endif

SUBDIRS = \
	$(AALIB_DIR) \
	$(CAIRO_DIR) \
	$(DV1394_DIR) \
	$(FLAC_DIR) \
	$(GDK_PIXBUF_DIR) \
	$(JACK_DIR) \
	$(JPEG_DIR) \
	$(LIBCACA_DIR) \
	$(LIBDE265_DIR) \
	$(LIBDV_DIR) \
	$(LIBMNG_DIR) \
	$(LIBPNG_DIR) \
	$(MIKMOD_DIR) \
	$(PULSE_DIR) \
	$(SHOUT2_DIR) \
	$(SOUP_DIR) \
	$(SPEEX_DIR) \
	$(TAGLIB_DIR) \
	$(VPX_DIR) \
	$(WAVPACK_DIR)

DIST_SUBDIRS = \
	aalib \
	cairo \
	dv \
	flac \
	gdk_pixbuf \
	jack \
	jpeg \
	libcaca \
	libde265 \
	libpng \
	pulse \
	raw1394 \
	shout2 \
	soup \
	speex \
	taglib \
	vpx \
	wavpack

include $(top_srcdir)/common/parallel-subdirs.mak
