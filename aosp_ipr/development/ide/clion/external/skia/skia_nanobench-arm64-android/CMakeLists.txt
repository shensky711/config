# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(skia_nanobench)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/skia/bench/AAClipBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/AlternatingColorPatternBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/AndroidCodecBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/BenchLogger.cpp
    ${ANDROID_ROOT}/external/skia/bench/Benchmark.cpp
    ${ANDROID_ROOT}/external/skia/bench/BezierBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/BigPathBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/BitmapBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/BitmapRectBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/BitmapRegionDecoderBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/BitmapScaleBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/BlendmodeBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/BlurBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/BlurImageFilterBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/BlurOccludedRRectBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/BlurRectBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/BlurRectsBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/BlurRoundRectBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/ChartBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/ChecksumBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/ChromeBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/ClipMaskBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/CmapBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/CodecBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/ColorCanvasDrawBitmapBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/ColorCodecBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/ColorFilterBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/ColorPrivBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/ControlBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/CoverageBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/CubicKLMBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/DashBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/DisplacementBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/DrawBitmapAABench.cpp
    ${ANDROID_ROOT}/external/skia/bench/DrawLatticeBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/EncoderBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/FSRectBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/FontCacheBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/FontScalerBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/GLBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/GLInstancedArraysBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/GLVec4ScalarBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/GLVertexAttributesBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/GMBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/GameBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/GeometryBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/GrMemoryPoolBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/GrMipMapBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/GrResourceCacheBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/GradientBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/HairlinePathBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/HardStopGradientBench_ScaleNumColors.cpp
    ${ANDROID_ROOT}/external/skia/bench/HardStopGradientBench_ScaleNumHardStops.cpp
    ${ANDROID_ROOT}/external/skia/bench/HardStopGradientBench_SpecialHardStops.cpp
    ${ANDROID_ROOT}/external/skia/bench/ImageBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/ImageCacheBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/ImageCacheBudgetBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/ImageFilterCollapse.cpp
    ${ANDROID_ROOT}/external/skia/bench/ImageFilterDAGBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/InterpBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/LightingBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/LineBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/MagnifierBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/MathBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/Matrix44Bench.cpp
    ${ANDROID_ROOT}/external/skia/bench/MatrixBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/MatrixConvolutionBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/MeasureBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/MemsetBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/MergeBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/MipMapBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/MorphologyBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/MutexBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/PDFBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/PatchBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/PathBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/PathIterBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/PathTextBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/PerlinNoiseBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/PictureNestingBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/PictureOverheadBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/PicturePlaybackBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/PremulAndUnpremulAlphaOpsBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/QuickRejectBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/RTreeBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/ReadPixBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/RecordingBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/RectBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/RectanizerBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/RectoriBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/RefCntBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/RegionBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/RegionContainBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/RepeatTileBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/RotatedRectBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/SKPAnimationBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/SKPBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/ScalarBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/ShaderMaskBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/ShadowBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/ShapesBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/Sk4fBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/SkBlend_optsBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/SkGlyphCacheBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/SkLinearBitmapPipelineBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/SkRasterPipelineBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/SortBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/StreamBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/StrokeBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/SwizzleBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/TableBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/TextBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/TextBlobBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/TileBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/TileImageFilterBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/TopoSortBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/VertBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/WritePixelsBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/WriterBench.cpp
    ${ANDROID_ROOT}/external/skia/bench/nanobench.cpp
    ${ANDROID_ROOT}/external/skia/bench/pack_int_uint16_t_Bench.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGAttribute.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGAttributeParser.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGCircle.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGClipPath.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGContainer.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGDOM.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGEllipse.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGLine.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGLinearGradient.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGNode.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGPath.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGPoly.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGRect.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGRenderContext.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGSVG.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGShape.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGStop.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGTransformableNode.cpp
    ${ANDROID_ROOT}/external/skia/experimental/svg/model/SkSVGValue.cpp
    ${ANDROID_ROOT}/external/skia/gm/OverStroke.cpp
    ${ANDROID_ROOT}/external/skia/gm/aaa.cpp
    ${ANDROID_ROOT}/external/skia/gm/aaclip.cpp
    ${ANDROID_ROOT}/external/skia/gm/aarectmodes.cpp
    ${ANDROID_ROOT}/external/skia/gm/aaxfermodes.cpp
    ${ANDROID_ROOT}/external/skia/gm/addarc.cpp
    ${ANDROID_ROOT}/external/skia/gm/all_bitmap_configs.cpp
    ${ANDROID_ROOT}/external/skia/gm/alphagradients.cpp
    ${ANDROID_ROOT}/external/skia/gm/animatedGif.cpp
    ${ANDROID_ROOT}/external/skia/gm/animatedimageblurs.cpp
    ${ANDROID_ROOT}/external/skia/gm/anisotropic.cpp
    ${ANDROID_ROOT}/external/skia/gm/annotated_text.cpp
    ${ANDROID_ROOT}/external/skia/gm/arcofzorro.cpp
    ${ANDROID_ROOT}/external/skia/gm/arcto.cpp
    ${ANDROID_ROOT}/external/skia/gm/arithmode.cpp
    ${ANDROID_ROOT}/external/skia/gm/badpaint.cpp
    ${ANDROID_ROOT}/external/skia/gm/beziereffects.cpp
    ${ANDROID_ROOT}/external/skia/gm/beziers.cpp
    ${ANDROID_ROOT}/external/skia/gm/bigblurs.cpp
    ${ANDROID_ROOT}/external/skia/gm/bigmatrix.cpp
    ${ANDROID_ROOT}/external/skia/gm/bigrect.cpp
    ${ANDROID_ROOT}/external/skia/gm/bigrrectaaeffect.cpp
    ${ANDROID_ROOT}/external/skia/gm/bigtext.cpp
    ${ANDROID_ROOT}/external/skia/gm/bigtileimagefilter.cpp
    ${ANDROID_ROOT}/external/skia/gm/bitmapcopy.cpp
    ${ANDROID_ROOT}/external/skia/gm/bitmapfilters.cpp
    ${ANDROID_ROOT}/external/skia/gm/bitmapimage.cpp
    ${ANDROID_ROOT}/external/skia/gm/bitmappremul.cpp
    ${ANDROID_ROOT}/external/skia/gm/bitmaprect.cpp
    ${ANDROID_ROOT}/external/skia/gm/bitmaprecttest.cpp
    ${ANDROID_ROOT}/external/skia/gm/bitmapshader.cpp
    ${ANDROID_ROOT}/external/skia/gm/bitmaptiled.cpp
    ${ANDROID_ROOT}/external/skia/gm/bleed.cpp
    ${ANDROID_ROOT}/external/skia/gm/blend.cpp
    ${ANDROID_ROOT}/external/skia/gm/blurcircles.cpp
    ${ANDROID_ROOT}/external/skia/gm/blurcircles2.cpp
    ${ANDROID_ROOT}/external/skia/gm/blurignorexform.cpp
    ${ANDROID_ROOT}/external/skia/gm/blurimagevmask.cpp
    ${ANDROID_ROOT}/external/skia/gm/blurquickreject.cpp
    ${ANDROID_ROOT}/external/skia/gm/blurrect.cpp
    ${ANDROID_ROOT}/external/skia/gm/blurredclippedcircle.cpp
    ${ANDROID_ROOT}/external/skia/gm/blurroundrect.cpp
    ${ANDROID_ROOT}/external/skia/gm/blurs.cpp
    ${ANDROID_ROOT}/external/skia/gm/bmpfilterqualityrepeat.cpp
    ${ANDROID_ROOT}/external/skia/gm/bug5252.cpp
    ${ANDROID_ROOT}/external/skia/gm/bug530095.cpp
    ${ANDROID_ROOT}/external/skia/gm/bug615686.cpp
    ${ANDROID_ROOT}/external/skia/gm/bug6643.cpp
    ${ANDROID_ROOT}/external/skia/gm/bug6783.cpp
    ${ANDROID_ROOT}/external/skia/gm/cgm.c
    ${ANDROID_ROOT}/external/skia/gm/cgms.cpp
    ${ANDROID_ROOT}/external/skia/gm/circles.cpp
    ${ANDROID_ROOT}/external/skia/gm/circulararcs.cpp
    ${ANDROID_ROOT}/external/skia/gm/circularclips.cpp
    ${ANDROID_ROOT}/external/skia/gm/clip_error.cpp
    ${ANDROID_ROOT}/external/skia/gm/clip_strokerect.cpp
    ${ANDROID_ROOT}/external/skia/gm/clipdrawdraw.cpp
    ${ANDROID_ROOT}/external/skia/gm/clippedbitmapshaders.cpp
    ${ANDROID_ROOT}/external/skia/gm/color4f.cpp
    ${ANDROID_ROOT}/external/skia/gm/coloremoji.cpp
    ${ANDROID_ROOT}/external/skia/gm/coloremoji_blendmodes.cpp
    ${ANDROID_ROOT}/external/skia/gm/colorfilteralpha8.cpp
    ${ANDROID_ROOT}/external/skia/gm/colorfilterimagefilter.cpp
    ${ANDROID_ROOT}/external/skia/gm/colorfilters.cpp
    ${ANDROID_ROOT}/external/skia/gm/colormatrix.cpp
    ${ANDROID_ROOT}/external/skia/gm/colorspacexform.cpp
    ${ANDROID_ROOT}/external/skia/gm/colorwheel.cpp
    ${ANDROID_ROOT}/external/skia/gm/complexclip.cpp
    ${ANDROID_ROOT}/external/skia/gm/complexclip2.cpp
    ${ANDROID_ROOT}/external/skia/gm/complexclip3.cpp
    ${ANDROID_ROOT}/external/skia/gm/complexclip4.cpp
    ${ANDROID_ROOT}/external/skia/gm/complexclip_blur_tiled.cpp
    ${ANDROID_ROOT}/external/skia/gm/composeshader.cpp
    ${ANDROID_ROOT}/external/skia/gm/concavepaths.cpp
    ${ANDROID_ROOT}/external/skia/gm/conicpaths.cpp
    ${ANDROID_ROOT}/external/skia/gm/constcolorprocessor.cpp
    ${ANDROID_ROOT}/external/skia/gm/convex_all_line_paths.cpp
    ${ANDROID_ROOT}/external/skia/gm/convexpaths.cpp
    ${ANDROID_ROOT}/external/skia/gm/convexpolyclip.cpp
    ${ANDROID_ROOT}/external/skia/gm/convexpolyeffect.cpp
    ${ANDROID_ROOT}/external/skia/gm/copyTo4444.cpp
    ${ANDROID_ROOT}/external/skia/gm/crbug_691386.cpp
    ${ANDROID_ROOT}/external/skia/gm/croppedrects.cpp
    ${ANDROID_ROOT}/external/skia/gm/crosscontextimage.cpp
    ${ANDROID_ROOT}/external/skia/gm/cubicpaths.cpp
    ${ANDROID_ROOT}/external/skia/gm/dashcircle.cpp
    ${ANDROID_ROOT}/external/skia/gm/dashcubics.cpp
    ${ANDROID_ROOT}/external/skia/gm/dashing.cpp
    ${ANDROID_ROOT}/external/skia/gm/deferredtextureimage.cpp
    ${ANDROID_ROOT}/external/skia/gm/degeneratesegments.cpp
    ${ANDROID_ROOT}/external/skia/gm/dftext.cpp
    ${ANDROID_ROOT}/external/skia/gm/discard.cpp
    ${ANDROID_ROOT}/external/skia/gm/displacement.cpp
    ${ANDROID_ROOT}/external/skia/gm/distantclip.cpp
    ${ANDROID_ROOT}/external/skia/gm/downsamplebitmap.cpp
    ${ANDROID_ROOT}/external/skia/gm/draw_bitmap_rect_skbug4374.cpp
    ${ANDROID_ROOT}/external/skia/gm/drawable.cpp
    ${ANDROID_ROOT}/external/skia/gm/drawatlas.cpp
    ${ANDROID_ROOT}/external/skia/gm/drawatlascolor.cpp
    ${ANDROID_ROOT}/external/skia/gm/drawbitmaprect.cpp
    ${ANDROID_ROOT}/external/skia/gm/drawfilter.cpp
    ${ANDROID_ROOT}/external/skia/gm/drawlooper.cpp
    ${ANDROID_ROOT}/external/skia/gm/drawminibitmaprect.cpp
    ${ANDROID_ROOT}/external/skia/gm/drawregion.cpp
    ${ANDROID_ROOT}/external/skia/gm/drawregionmodes.cpp
    ${ANDROID_ROOT}/external/skia/gm/dropshadowimagefilter.cpp
    ${ANDROID_ROOT}/external/skia/gm/drrect.cpp
    ${ANDROID_ROOT}/external/skia/gm/dstreadshuffle.cpp
    ${ANDROID_ROOT}/external/skia/gm/emboss.cpp
    ${ANDROID_ROOT}/external/skia/gm/emptypath.cpp
    ${ANDROID_ROOT}/external/skia/gm/encode-alpha-jpeg.cpp
    ${ANDROID_ROOT}/external/skia/gm/encode-platform.cpp
    ${ANDROID_ROOT}/external/skia/gm/encode-srgb.cpp
    ${ANDROID_ROOT}/external/skia/gm/encode.cpp
    ${ANDROID_ROOT}/external/skia/gm/extractbitmap.cpp
    ${ANDROID_ROOT}/external/skia/gm/fadefilter.cpp
    ${ANDROID_ROOT}/external/skia/gm/fatpathfill.cpp
    ${ANDROID_ROOT}/external/skia/gm/filltypes.cpp
    ${ANDROID_ROOT}/external/skia/gm/filltypespersp.cpp
    ${ANDROID_ROOT}/external/skia/gm/filterbitmap.cpp
    ${ANDROID_ROOT}/external/skia/gm/filterbug.cpp
    ${ANDROID_ROOT}/external/skia/gm/filterfastbounds.cpp
    ${ANDROID_ROOT}/external/skia/gm/filterindiabox.cpp
    ${ANDROID_ROOT}/external/skia/gm/fontcache.cpp
    ${ANDROID_ROOT}/external/skia/gm/fontmgr.cpp
    ${ANDROID_ROOT}/external/skia/gm/fontscaler.cpp
    ${ANDROID_ROOT}/external/skia/gm/fontscalerdistortable.cpp
    ${ANDROID_ROOT}/external/skia/gm/gamma.cpp
    ${ANDROID_ROOT}/external/skia/gm/gammaencodedpremul.cpp
    ${ANDROID_ROOT}/external/skia/gm/gammatext.cpp
    ${ANDROID_ROOT}/external/skia/gm/gamut.cpp
    ${ANDROID_ROOT}/external/skia/gm/getpostextpath.cpp
    ${ANDROID_ROOT}/external/skia/gm/giantbitmap.cpp
    ${ANDROID_ROOT}/external/skia/gm/glyph_pos.cpp
    ${ANDROID_ROOT}/external/skia/gm/glyph_pos_align.cpp
    ${ANDROID_ROOT}/external/skia/gm/gm.cpp
    ${ANDROID_ROOT}/external/skia/gm/gradientDirtyLaundry.cpp
    ${ANDROID_ROOT}/external/skia/gm/gradient_matrix.cpp
    ${ANDROID_ROOT}/external/skia/gm/gradients.cpp
    ${ANDROID_ROOT}/external/skia/gm/gradients_2pt_conical.cpp
    ${ANDROID_ROOT}/external/skia/gm/gradients_no_texture.cpp
    ${ANDROID_ROOT}/external/skia/gm/gradtext.cpp
    ${ANDROID_ROOT}/external/skia/gm/grayscalejpg.cpp
    ${ANDROID_ROOT}/external/skia/gm/hairlines.cpp
    ${ANDROID_ROOT}/external/skia/gm/hairmodes.cpp
    ${ANDROID_ROOT}/external/skia/gm/hardstop_gradients.cpp
    ${ANDROID_ROOT}/external/skia/gm/highcontrastfilter.cpp
    ${ANDROID_ROOT}/external/skia/gm/hittestpath.cpp
    ${ANDROID_ROOT}/external/skia/gm/hsl.cpp
    ${ANDROID_ROOT}/external/skia/gm/image.cpp
    ${ANDROID_ROOT}/external/skia/gm/image_pict.cpp
    ${ANDROID_ROOT}/external/skia/gm/image_shader.cpp
    ${ANDROID_ROOT}/external/skia/gm/imagealphathreshold.cpp
    ${ANDROID_ROOT}/external/skia/gm/imageblur.cpp
    ${ANDROID_ROOT}/external/skia/gm/imageblur2.cpp
    ${ANDROID_ROOT}/external/skia/gm/imageblurclampmode.cpp
    ${ANDROID_ROOT}/external/skia/gm/imageblurrepeatmode.cpp
    ${ANDROID_ROOT}/external/skia/gm/imageblurtiled.cpp
    ${ANDROID_ROOT}/external/skia/gm/imagefilters.cpp
    ${ANDROID_ROOT}/external/skia/gm/imagefiltersbase.cpp
    ${ANDROID_ROOT}/external/skia/gm/imagefiltersclipped.cpp
    ${ANDROID_ROOT}/external/skia/gm/imagefilterscropexpand.cpp
    ${ANDROID_ROOT}/external/skia/gm/imagefilterscropped.cpp
    ${ANDROID_ROOT}/external/skia/gm/imagefiltersgraph.cpp
    ${ANDROID_ROOT}/external/skia/gm/imagefiltersscaled.cpp
    ${ANDROID_ROOT}/external/skia/gm/imagefiltersstroked.cpp
    ${ANDROID_ROOT}/external/skia/gm/imagefilterstransformed.cpp
    ${ANDROID_ROOT}/external/skia/gm/imagefromyuvtextures.cpp
    ${ANDROID_ROOT}/external/skia/gm/imagemagnifier.cpp
    ${ANDROID_ROOT}/external/skia/gm/imagemakewithfilter.cpp
    ${ANDROID_ROOT}/external/skia/gm/imagemasksubset.cpp
    ${ANDROID_ROOT}/external/skia/gm/imageresizetiled.cpp
    ${ANDROID_ROOT}/external/skia/gm/imagescalealigned.cpp
    ${ANDROID_ROOT}/external/skia/gm/imagesource.cpp
    ${ANDROID_ROOT}/external/skia/gm/imagesource2.cpp
    ${ANDROID_ROOT}/external/skia/gm/internal_links.cpp
    ${ANDROID_ROOT}/external/skia/gm/inversepaths.cpp
    ${ANDROID_ROOT}/external/skia/gm/largeglyphblur.cpp
    ${ANDROID_ROOT}/external/skia/gm/lattice.cpp
    ${ANDROID_ROOT}/external/skia/gm/lcdblendmodes.cpp
    ${ANDROID_ROOT}/external/skia/gm/lcdoverlap.cpp
    ${ANDROID_ROOT}/external/skia/gm/lcdtext.cpp
    ${ANDROID_ROOT}/external/skia/gm/lighting.cpp
    ${ANDROID_ROOT}/external/skia/gm/lightingshader.cpp
    ${ANDROID_ROOT}/external/skia/gm/lightingshader2.cpp
    ${ANDROID_ROOT}/external/skia/gm/linepaths.cpp
    ${ANDROID_ROOT}/external/skia/gm/localmatriximagefilter.cpp
    ${ANDROID_ROOT}/external/skia/gm/localmatriximageshader.cpp
    ${ANDROID_ROOT}/external/skia/gm/lumafilter.cpp
    ${ANDROID_ROOT}/external/skia/gm/makecolorspace.cpp
    ${ANDROID_ROOT}/external/skia/gm/manypaths.cpp
    ${ANDROID_ROOT}/external/skia/gm/matrixconvolution.cpp
    ${ANDROID_ROOT}/external/skia/gm/matriximagefilter.cpp
    ${ANDROID_ROOT}/external/skia/gm/megalooper.cpp
    ${ANDROID_ROOT}/external/skia/gm/mipmap.cpp
    ${ANDROID_ROOT}/external/skia/gm/mixedtextblobs.cpp
    ${ANDROID_ROOT}/external/skia/gm/modecolorfilters.cpp
    ${ANDROID_ROOT}/external/skia/gm/morphology.cpp
    ${ANDROID_ROOT}/external/skia/gm/multipicturedraw.cpp
    ${ANDROID_ROOT}/external/skia/gm/nested.cpp
    ${ANDROID_ROOT}/external/skia/gm/ninepatchstretch.cpp
    ${ANDROID_ROOT}/external/skia/gm/nonclosedpaths.cpp
    ${ANDROID_ROOT}/external/skia/gm/occludedrrectblur.cpp
    ${ANDROID_ROOT}/external/skia/gm/offsetimagefilter.cpp
    ${ANDROID_ROOT}/external/skia/gm/ovals.cpp
    ${ANDROID_ROOT}/external/skia/gm/overdrawcolorfilter.cpp
    ${ANDROID_ROOT}/external/skia/gm/patch.cpp
    ${ANDROID_ROOT}/external/skia/gm/path_stroke_with_zero_length.cpp
    ${ANDROID_ROOT}/external/skia/gm/pathcontourstart.cpp
    ${ANDROID_ROOT}/external/skia/gm/patheffects.cpp
    ${ANDROID_ROOT}/external/skia/gm/pathfill.cpp
    ${ANDROID_ROOT}/external/skia/gm/pathinterior.cpp
    ${ANDROID_ROOT}/external/skia/gm/pathmaskcache.cpp
    ${ANDROID_ROOT}/external/skia/gm/pathopsinverse.cpp
    ${ANDROID_ROOT}/external/skia/gm/pathopsskpclip.cpp
    ${ANDROID_ROOT}/external/skia/gm/pathreverse.cpp
    ${ANDROID_ROOT}/external/skia/gm/pdf_never_embed.cpp
    ${ANDROID_ROOT}/external/skia/gm/perlinnoise.cpp
    ${ANDROID_ROOT}/external/skia/gm/perspshaders.cpp
    ${ANDROID_ROOT}/external/skia/gm/picture.cpp
    ${ANDROID_ROOT}/external/skia/gm/pictureimagefilter.cpp
    ${ANDROID_ROOT}/external/skia/gm/pictureimagegenerator.cpp
    ${ANDROID_ROOT}/external/skia/gm/pictureshader.cpp
    ${ANDROID_ROOT}/external/skia/gm/pictureshadercache.cpp
    ${ANDROID_ROOT}/external/skia/gm/pictureshadertile.cpp
    ${ANDROID_ROOT}/external/skia/gm/pixelsnap.cpp
    ${ANDROID_ROOT}/external/skia/gm/plus.cpp
    ${ANDROID_ROOT}/external/skia/gm/points.cpp
    ${ANDROID_ROOT}/external/skia/gm/poly2poly.cpp
    ${ANDROID_ROOT}/external/skia/gm/polygons.cpp
    ${ANDROID_ROOT}/external/skia/gm/quadpaths.cpp
    ${ANDROID_ROOT}/external/skia/gm/radial_gradient_precision.cpp
    ${ANDROID_ROOT}/external/skia/gm/readpixels.cpp
    ${ANDROID_ROOT}/external/skia/gm/recordopts.cpp
    ${ANDROID_ROOT}/external/skia/gm/rectangletexture.cpp
    ${ANDROID_ROOT}/external/skia/gm/rects.cpp
    ${ANDROID_ROOT}/external/skia/gm/repeated_bitmap.cpp
    ${ANDROID_ROOT}/external/skia/gm/resizeimagefilter.cpp
    ${ANDROID_ROOT}/external/skia/gm/reveal.cpp
    ${ANDROID_ROOT}/external/skia/gm/roundrects.cpp
    ${ANDROID_ROOT}/external/skia/gm/rrect.cpp
    ${ANDROID_ROOT}/external/skia/gm/rrectclipdrawpaint.cpp
    ${ANDROID_ROOT}/external/skia/gm/rrects.cpp
    ${ANDROID_ROOT}/external/skia/gm/samplerstress.cpp
    ${ANDROID_ROOT}/external/skia/gm/savelayer.cpp
    ${ANDROID_ROOT}/external/skia/gm/scaledstrokes.cpp
    ${ANDROID_ROOT}/external/skia/gm/shaderbounds.cpp
    ${ANDROID_ROOT}/external/skia/gm/shadertext.cpp
    ${ANDROID_ROOT}/external/skia/gm/shadertext2.cpp
    ${ANDROID_ROOT}/external/skia/gm/shadertext3.cpp
    ${ANDROID_ROOT}/external/skia/gm/shadows.cpp
    ${ANDROID_ROOT}/external/skia/gm/shadowutils.cpp
    ${ANDROID_ROOT}/external/skia/gm/shallowgradient.cpp
    ${ANDROID_ROOT}/external/skia/gm/shapes.cpp
    ${ANDROID_ROOT}/external/skia/gm/shapes_as_paths.cpp
    ${ANDROID_ROOT}/external/skia/gm/showmiplevels.cpp
    ${ANDROID_ROOT}/external/skia/gm/simple_magnification.cpp
    ${ANDROID_ROOT}/external/skia/gm/simpleaaclip.cpp
    ${ANDROID_ROOT}/external/skia/gm/simplerect.cpp
    ${ANDROID_ROOT}/external/skia/gm/skbug1719.cpp
    ${ANDROID_ROOT}/external/skia/gm/skbug_257.cpp
    ${ANDROID_ROOT}/external/skia/gm/skbug_4868.cpp
    ${ANDROID_ROOT}/external/skia/gm/skbug_5321.cpp
    ${ANDROID_ROOT}/external/skia/gm/smallarc.cpp
    ${ANDROID_ROOT}/external/skia/gm/smallimage.cpp
    ${ANDROID_ROOT}/external/skia/gm/smallpaths.cpp
    ${ANDROID_ROOT}/external/skia/gm/spritebitmap.cpp
    ${ANDROID_ROOT}/external/skia/gm/srcmode.cpp
    ${ANDROID_ROOT}/external/skia/gm/srgb.cpp
    ${ANDROID_ROOT}/external/skia/gm/stlouisarch.cpp
    ${ANDROID_ROOT}/external/skia/gm/stringart.cpp
    ${ANDROID_ROOT}/external/skia/gm/stroke_rect_shader.cpp
    ${ANDROID_ROOT}/external/skia/gm/strokedlines.cpp
    ${ANDROID_ROOT}/external/skia/gm/strokefill.cpp
    ${ANDROID_ROOT}/external/skia/gm/strokerect.cpp
    ${ANDROID_ROOT}/external/skia/gm/strokerects.cpp
    ${ANDROID_ROOT}/external/skia/gm/strokes.cpp
    ${ANDROID_ROOT}/external/skia/gm/stroketext.cpp
    ${ANDROID_ROOT}/external/skia/gm/subsetshader.cpp
    ${ANDROID_ROOT}/external/skia/gm/surface.cpp
    ${ANDROID_ROOT}/external/skia/gm/tablecolorfilter.cpp
    ${ANDROID_ROOT}/external/skia/gm/tallstretchedbitmaps.cpp
    ${ANDROID_ROOT}/external/skia/gm/testgradient.cpp
    ${ANDROID_ROOT}/external/skia/gm/texdata.cpp
    ${ANDROID_ROOT}/external/skia/gm/textblob.cpp
    ${ANDROID_ROOT}/external/skia/gm/textblobblockreordering.cpp
    ${ANDROID_ROOT}/external/skia/gm/textblobcolortrans.cpp
    ${ANDROID_ROOT}/external/skia/gm/textblobgeometrychange.cpp
    ${ANDROID_ROOT}/external/skia/gm/textbloblooper.cpp
    ${ANDROID_ROOT}/external/skia/gm/textblobmixedsizes.cpp
    ${ANDROID_ROOT}/external/skia/gm/textblobrandomfont.cpp
    ${ANDROID_ROOT}/external/skia/gm/textblobshader.cpp
    ${ANDROID_ROOT}/external/skia/gm/textblobtransforms.cpp
    ${ANDROID_ROOT}/external/skia/gm/textblobuseaftergpufree.cpp
    ${ANDROID_ROOT}/external/skia/gm/texteffects.cpp
    ${ANDROID_ROOT}/external/skia/gm/texturedomaineffect.cpp
    ${ANDROID_ROOT}/external/skia/gm/thinconcavepaths.cpp
    ${ANDROID_ROOT}/external/skia/gm/thinrects.cpp
    ${ANDROID_ROOT}/external/skia/gm/thinstrokedrects.cpp
    ${ANDROID_ROOT}/external/skia/gm/tiledscaledbitmap.cpp
    ${ANDROID_ROOT}/external/skia/gm/tileimagefilter.cpp
    ${ANDROID_ROOT}/external/skia/gm/tilemodes.cpp
    ${ANDROID_ROOT}/external/skia/gm/tilemodes_scaled.cpp
    ${ANDROID_ROOT}/external/skia/gm/tinybitmap.cpp
    ${ANDROID_ROOT}/external/skia/gm/transparency.cpp
    ${ANDROID_ROOT}/external/skia/gm/typeface.cpp
    ${ANDROID_ROOT}/external/skia/gm/variedtext.cpp
    ${ANDROID_ROOT}/external/skia/gm/vertices.cpp
    ${ANDROID_ROOT}/external/skia/gm/verttext.cpp
    ${ANDROID_ROOT}/external/skia/gm/verttext2.cpp
    ${ANDROID_ROOT}/external/skia/gm/verylargebitmap.cpp
    ${ANDROID_ROOT}/external/skia/gm/windowrectangles.cpp
    ${ANDROID_ROOT}/external/skia/gm/xfermodeimagefilter.cpp
    ${ANDROID_ROOT}/external/skia/gm/xfermodes.cpp
    ${ANDROID_ROOT}/external/skia/gm/xfermodes2.cpp
    ${ANDROID_ROOT}/external/skia/gm/xfermodes3.cpp
    ${ANDROID_ROOT}/external/skia/gm/xform_image_gen.cpp
    ${ANDROID_ROOT}/external/skia/gm/yuvtorgbeffect.cpp
    ${ANDROID_ROOT}/external/skia/tools/AndroidSkDebugToStdOut.cpp
    ${ANDROID_ROOT}/external/skia/tools/CrashHandler.cpp
    ${ANDROID_ROOT}/external/skia/tools/LsanSuppressions.cpp
    ${ANDROID_ROOT}/external/skia/tools/ProcStats.cpp
    ${ANDROID_ROOT}/external/skia/tools/Resources.cpp
    ${ANDROID_ROOT}/external/skia/tools/ThermalManager.cpp
    ${ANDROID_ROOT}/external/skia/tools/UrlDataManager.cpp
    ${ANDROID_ROOT}/external/skia/tools/debugger/SkDebugCanvas.cpp
    ${ANDROID_ROOT}/external/skia/tools/debugger/SkDrawCommand.cpp
    ${ANDROID_ROOT}/external/skia/tools/debugger/SkJsonWriteBuffer.cpp
    ${ANDROID_ROOT}/external/skia/tools/debugger/SkObjectParser.cpp
    ${ANDROID_ROOT}/external/skia/tools/flags/SkCommandLineFlags.cpp
    ${ANDROID_ROOT}/external/skia/tools/flags/SkCommonFlags.cpp
    ${ANDROID_ROOT}/external/skia/tools/flags/SkCommonFlagsConfig.cpp
    ${ANDROID_ROOT}/external/skia/tools/gpu/GrContextFactory.cpp
    ${ANDROID_ROOT}/external/skia/tools/gpu/GrTest.cpp
    ${ANDROID_ROOT}/external/skia/tools/gpu/TestContext.cpp
    ${ANDROID_ROOT}/external/skia/tools/gpu/gl/GLTestContext.cpp
    ${ANDROID_ROOT}/external/skia/tools/gpu/gl/command_buffer/GLTestContext_command_buffer.cpp
    ${ANDROID_ROOT}/external/skia/tools/gpu/gl/debug/DebugGLTestContext.cpp
    ${ANDROID_ROOT}/external/skia/tools/gpu/gl/debug/GrBufferObj.cpp
    ${ANDROID_ROOT}/external/skia/tools/gpu/gl/debug/GrFrameBufferObj.cpp
    ${ANDROID_ROOT}/external/skia/tools/gpu/gl/debug/GrProgramObj.cpp
    ${ANDROID_ROOT}/external/skia/tools/gpu/gl/debug/GrShaderObj.cpp
    ${ANDROID_ROOT}/external/skia/tools/gpu/gl/debug/GrTextureObj.cpp
    ${ANDROID_ROOT}/external/skia/tools/gpu/gl/debug/GrTextureUnitObj.cpp
    ${ANDROID_ROOT}/external/skia/tools/gpu/gl/egl/CreatePlatformGLTestContext_egl.cpp
    ${ANDROID_ROOT}/external/skia/tools/gpu/gl/null/NullGLTestContext.cpp
    ${ANDROID_ROOT}/external/skia/tools/gpu/mock/MockTestContext.cpp
    ${ANDROID_ROOT}/external/skia/tools/gpu/vk/VkTestContext.cpp
    ${ANDROID_ROOT}/external/skia/tools/picture_utils.cpp
    ${ANDROID_ROOT}/external/skia/tools/random_parse_path.cpp
    ${ANDROID_ROOT}/external/skia/tools/sk_tool_utils.cpp
    ${ANDROID_ROOT}/external/skia/tools/sk_tool_utils_font.cpp
    ${ANDROID_ROOT}/external/skia/tools/timer/Timer.cpp
    ${ANDROID_ROOT}/external/skia/tools/trace/SkDebugfTracer.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/skia/bench -Iexternal/skia/experimental/svg/model -Iexternal/skia/gm -Iexternal/skia/include/android -Iexternal/skia/include/c -Iexternal/skia/include/codec -Iexternal/skia/include/config -Iexternal/skia/include/core -Iexternal/skia/include/effects -Iexternal/skia/include/encode -Iexternal/skia/include/gpu -Iexternal/skia/include/gpu/gl -Iexternal/skia/include/gpu/vk -Iexternal/skia/include/pathops -Iexternal/skia/include/ports -Iexternal/skia/include/private -Iexternal/skia/include/svg -Iexternal/skia/include/utils -Iexternal/skia/include/utils/mac -Iexternal/skia/src/c -Iexternal/skia/src/codec -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/fonts -Iexternal/skia/src/gpu -Iexternal/skia/src/image -Iexternal/skia/src/images -Iexternal/skia/src/lazy -Iexternal/skia/src/opts -Iexternal/skia/src/pathops -Iexternal/skia/src/pdf -Iexternal/skia/src/ports -Iexternal/skia/src/sfnt -Iexternal/skia/src/shaders -Iexternal/skia/src/shaders/gradients -Iexternal/skia/src/sksl -Iexternal/skia/src/utils -Iexternal/skia/src/utils/win -Iexternal/skia/src/xml -Iexternal/skia/third_party/gif -Iexternal/skia/tools -Iexternal/skia/tools/debugger -Iexternal/skia/tools/flags -Iexternal/skia/tools/gpu -Iexternal/skia/tools/timer -Iexternal/skia/tools/trace'
# Raw param [1] = '-Iexternal/skia'
# Raw param [2] = ''
# Raw param [3] = '${config.Arm64ClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.DeviceClangGlobalCflags}'
# Raw param [6] = ''
# Raw param [7] = '-Iexternal/googletest/googletest/include'
# Raw param [8] = '-Iframeworks/native/libs/arect/include'
# Raw param [9] = '-Iexternal/jsoncpp/include'
# Raw param [10] = '-Iexternal/skia/include/android'
# Raw param [11] = '-Iexternal/skia/include/c'
# Raw param [12] = '-Iexternal/skia/include/codec'
# Raw param [13] = '-Iexternal/skia/include/config'
# Raw param [14] = '-Iexternal/skia/include/core'
# Raw param [15] = '-Iexternal/skia/include/effects'
# Raw param [16] = '-Iexternal/skia/include/encode'
# Raw param [17] = '-Iexternal/skia/include/gpu'
# Raw param [18] = '-Iexternal/skia/include/gpu/gl'
# Raw param [19] = '-Iexternal/skia/include/gpu/vk'
# Raw param [20] = '-Iexternal/skia/include/pathops'
# Raw param [21] = '-Iexternal/skia/include/ports'
# Raw param [22] = '-Iexternal/skia/include/svg'
# Raw param [23] = '-Iexternal/skia/include/utils'
# Raw param [24] = '-Iexternal/skia/include/utils/mac'
# Raw param [25] = '-Iexternal/sfntly/cpp/src'
# Raw param [26] = '-Iexternal/webp/include'
# Raw param [27] = '-Iframeworks/native/opengl/libs/EGL/include'
# Raw param [28] = '-Iframeworks/native/opengl/include'
# Raw param [29] = '-Isystem/core/libcutils/include'
# Raw param [30] = '-Iexternal/dng_sdk/source'
# Raw param [31] = '-Iexternal/expat/lib'
# Raw param [32] = '-Iexternal/freetype/include'
# Raw param [33] = '-Iframeworks/av/media/libheif/include'
# Raw param [34] = '-Iexternal/icu/icu4c/source/i18n'
# Raw param [35] = '-Iexternal/icu/icu4c/source/common'
# Raw param [36] = '-Iexternal/libjpeg-turbo'
# Raw param [37] = '-Isystem/core/liblog/include'
# Raw param [38] = '-Iframeworks/native/libs/nativewindow/include'
# Raw param [39] = '-Iframeworks/native/libs/nativebase/include'
# Raw param [40] = '-Iexternal/piex'
# Raw param [41] = '-Iexternal/libpng'
# Raw param [42] = '-Iframeworks/native/vulkan/include'
# Raw param [43] = '-Ihardware/libhardware/include'
# Raw param [44] = '-Isystem/media/audio/include'
# Raw param [45] = '-Isystem/core/libsystem/include'
# Raw param [46] = '-Iexternal/zlib'
# Raw param [47] = '-Iexternal/libcxx/include'
# Raw param [48] = '-Iexternal/libcxxabi/include'
# variable ${config.Arm64ClangCflags} = '-fno-exceptions -Wno-multichar -fno-strict-aliasing -fstack-protector-strong -ffunction-sections -fdata-sections -funwind-tables -Wa,--noexecstack -Werror=format-security -D_FORTIFY_SOURCE=2 -fno-short-enums -no-canonical-prefixes -Werror=pointer-to-int-cast -Werror=int-to-pointer-cast -Werror=implicit-function-declaration -DNDEBUG -O2 -g -Wstrict-aliasing=2'
# Raw param [0] = '-fno-exceptions'
# Raw param [1] = '-Wno-multichar'
# Raw param [2] = '-fno-strict-aliasing'
# Raw param [3] = '-fstack-protector-strong'
# Raw param [4] = '-ffunction-sections'
# Raw param [5] = '-fdata-sections'
# Raw param [6] = '-funwind-tables'
# Raw param [7] = '-Wa,--noexecstack'
# Raw param [8] = '-Werror=format-security'
# Raw param [9] = '-D_FORTIFY_SOURCE=2'
# Raw param [10] = '-fno-short-enums'
# Raw param [11] = '-no-canonical-prefixes'
# Raw param [12] = '-Werror=pointer-to-int-cast'
# Raw param [13] = '-Werror=int-to-pointer-cast'
# Raw param [14] = '-Werror=implicit-function-declaration'
# Raw param [15] = '-DNDEBUG'
# Raw param [16] = '-O2'
# Raw param [17] = '-g'
# Raw param [18] = '-Wstrict-aliasing=2'
# FLAG '-fno-exceptions' became -fno-exceptions
# FLAG '-Wno-multichar' became -Wno-multichar
# FLAG '-fno-strict-aliasing' became -fno-strict-aliasing
# FLAG '-fstack-protector-strong' became -fstack-protector-strong
# FLAG '-ffunction-sections' became -ffunction-sections
# FLAG '-fdata-sections' became -fdata-sections
# FLAG '-funwind-tables' became -funwind-tables
# FLAG '-Wa,--noexecstack' became -Wa,--noexecstack
# FLAG '-Werror=format-security' became -Werror=format-security
# FLAG '-D_FORTIFY_SOURCE=2' became -D_FORTIFY_SOURCE=2
# FLAG '-fno-short-enums' became -fno-short-enums
# FLAG '-no-canonical-prefixes' became -no-canonical-prefixes
# FLAG '-Werror=pointer-to-int-cast' became -Werror=pointer-to-int-cast
# FLAG '-Werror=int-to-pointer-cast' became -Werror=int-to-pointer-cast
# FLAG '-Werror=implicit-function-declaration' became -Werror=implicit-function-declaration
# FLAG '-DNDEBUG' became -DNDEBUG
# FLAG '-O2' became -O2
# FLAG '-g' became -g
# FLAG '-Wstrict-aliasing=2' became -Wstrict-aliasing=2
# variable ${config.CommonClangGlobalCflags} = '-DANDROID -fmessage-length=0 -W -Wall -Wno-unused -Winit-self -Wpointer-arith -DNDEBUG -UDEBUG -fdebug-prefix-map=/proc/self/cwd= -D__compiler_offsetof=__builtin_offsetof -Werror=int-conversion -Wno-reserved-id-macro -Wno-format-pedantic -Wno-unused-command-line-argument -fcolor-diagnostics -Wno-expansion-to-defined -fdebug-prefix-map=$$PWD/='
# Raw param [0] = '-DANDROID'
# Raw param [1] = '-fmessage-length=0'
# Raw param [2] = '-W'
# Raw param [3] = '-Wall'
# Raw param [4] = '-Wno-unused'
# Raw param [5] = '-Winit-self'
# Raw param [6] = '-Wpointer-arith'
# Raw param [7] = '-DNDEBUG'
# Raw param [8] = '-UDEBUG'
# Raw param [9] = '-fdebug-prefix-map=/proc/self/cwd='
# Raw param [10] = '-D__compiler_offsetof=__builtin_offsetof'
# Raw param [11] = '-Werror=int-conversion'
# Raw param [12] = '-Wno-reserved-id-macro'
# Raw param [13] = '-Wno-format-pedantic'
# Raw param [14] = '-Wno-unused-command-line-argument'
# Raw param [15] = '-fcolor-diagnostics'
# Raw param [16] = '-Wno-expansion-to-defined'
# Raw param [17] = '-fdebug-prefix-map=$$PWD/='
# FLAG '-DANDROID' became -DANDROID
# FLAG '-fmessage-length=0' became -fmessage-length=0
# FLAG '-W' became -W
# FLAG '-Wall' became -Wall
# FLAG '-Wno-unused' became -Wno-unused
# FLAG '-Winit-self' became -Winit-self
# FLAG '-Wpointer-arith' became -Wpointer-arith
# FLAG '-DNDEBUG' became -DNDEBUG
# FLAG '-UDEBUG' became -UDEBUG
# FLAG '-fdebug-prefix-map=/proc/self/cwd=' became -fdebug-prefix-map=/proc/self/cwd=
# FLAG '-D__compiler_offsetof=__builtin_offsetof' became -D__compiler_offsetof=__builtin_offsetof
# FLAG '-Werror=int-conversion' became -Werror=int-conversion
# FLAG '-Wno-reserved-id-macro' became -Wno-reserved-id-macro
# FLAG '-Wno-format-pedantic' became -Wno-format-pedantic
# FLAG '-Wno-unused-command-line-argument' became -Wno-unused-command-line-argument
# FLAG '-fcolor-diagnostics' became -fcolor-diagnostics
# FLAG '-Wno-expansion-to-defined' became -Wno-expansion-to-defined
# FLAG '-fdebug-prefix-map=$$PWD/=' became -fdebug-prefix-map=$$PWD/=
# variable ${config.DeviceClangGlobalCflags} = '-Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Werror=date-time -nostdlibinc'
# Raw param [0] = '-Werror=return-type'
# Raw param [1] = '-Werror=non-virtual-dtor'
# Raw param [2] = '-Werror=address'
# Raw param [3] = '-Werror=sequence-point'
# Raw param [4] = '-Werror=date-time'
# Raw param [5] = '-nostdlibinc'
# FLAG '-Werror=return-type' became -Werror=return-type
# FLAG '-Werror=non-virtual-dtor' became -Werror=non-virtual-dtor
# FLAG '-Werror=address' became -Werror=address
# FLAG '-Werror=sequence-point' became -Werror=sequence-point
# FLAG '-Werror=date-time' became -Werror=date-time
# FLAG '-nostdlibinc' became -nostdlibinc
include_directories( 
    "${ANDROID_ROOT}/external/skia/bench -Iexternal/skia/experimental/svg/model -Iexternal/skia/gm -Iexternal/skia/include/android -Iexternal/skia/include/c -Iexternal/skia/include/codec -Iexternal/skia/include/config -Iexternal/skia/include/core -Iexternal/skia/include/effects -Iexternal/skia/include/encode -Iexternal/skia/include/gpu -Iexternal/skia/include/gpu/gl -Iexternal/skia/include/gpu/vk -Iexternal/skia/include/pathops -Iexternal/skia/include/ports -Iexternal/skia/include/private -Iexternal/skia/include/svg -Iexternal/skia/include/utils -Iexternal/skia/include/utils/mac -Iexternal/skia/src/c -Iexternal/skia/src/codec -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/fonts -Iexternal/skia/src/gpu -Iexternal/skia/src/image -Iexternal/skia/src/images -Iexternal/skia/src/lazy -Iexternal/skia/src/opts -Iexternal/skia/src/pathops -Iexternal/skia/src/pdf -Iexternal/skia/src/ports -Iexternal/skia/src/sfnt -Iexternal/skia/src/shaders -Iexternal/skia/src/shaders/gradients -Iexternal/skia/src/sksl -Iexternal/skia/src/utils -Iexternal/skia/src/utils/win -Iexternal/skia/src/xml -Iexternal/skia/third_party/gif -Iexternal/skia/tools -Iexternal/skia/tools/debugger -Iexternal/skia/tools/flags -Iexternal/skia/tools/gpu -Iexternal/skia/tools/timer -Iexternal/skia/tools/trace"
    "${ANDROID_ROOT}/external/skia"
    "${ANDROID_ROOT}/external/googletest/googletest/include"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include"
    "${ANDROID_ROOT}/external/jsoncpp/include"
    "${ANDROID_ROOT}/external/skia/include/android"
    "${ANDROID_ROOT}/external/skia/include/c"
    "${ANDROID_ROOT}/external/skia/include/codec"
    "${ANDROID_ROOT}/external/skia/include/config"
    "${ANDROID_ROOT}/external/skia/include/core"
    "${ANDROID_ROOT}/external/skia/include/effects"
    "${ANDROID_ROOT}/external/skia/include/encode"
    "${ANDROID_ROOT}/external/skia/include/gpu"
    "${ANDROID_ROOT}/external/skia/include/gpu/gl"
    "${ANDROID_ROOT}/external/skia/include/gpu/vk"
    "${ANDROID_ROOT}/external/skia/include/pathops"
    "${ANDROID_ROOT}/external/skia/include/ports"
    "${ANDROID_ROOT}/external/skia/include/svg"
    "${ANDROID_ROOT}/external/skia/include/utils"
    "${ANDROID_ROOT}/external/skia/include/utils/mac"
    "${ANDROID_ROOT}/external/sfntly/cpp/src"
    "${ANDROID_ROOT}/external/webp/include"
    "${ANDROID_ROOT}/frameworks/native/opengl/libs/EGL/include"
    "${ANDROID_ROOT}/frameworks/native/opengl/include"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/external/dng_sdk/source"
    "${ANDROID_ROOT}/external/expat/lib"
    "${ANDROID_ROOT}/external/freetype/include"
    "${ANDROID_ROOT}/frameworks/av/media/libheif/include"
    "${ANDROID_ROOT}/external/icu/icu4c/source/i18n"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common"
    "${ANDROID_ROOT}/external/libjpeg-turbo"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include"
    "${ANDROID_ROOT}/frameworks/native/libs/nativebase/include"
    "${ANDROID_ROOT}/external/piex"
    "${ANDROID_ROOT}/external/libpng"
    "${ANDROID_ROOT}/frameworks/native/vulkan/include"
    "${ANDROID_ROOT}/hardware/libhardware/include"
    "${ANDROID_ROOT}/system/media/audio/include"
    "${ANDROID_ROOT}/system/core/libsystem/include"
    "${ANDROID_ROOT}/external/zlib"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/skia/bench -Iexternal/skia/experimental/svg/model -Iexternal/skia/gm -Iexternal/skia/include/android -Iexternal/skia/include/c -Iexternal/skia/include/codec -Iexternal/skia/include/config -Iexternal/skia/include/core -Iexternal/skia/include/effects -Iexternal/skia/include/encode -Iexternal/skia/include/gpu -Iexternal/skia/include/gpu/gl -Iexternal/skia/include/gpu/vk -Iexternal/skia/include/pathops -Iexternal/skia/include/ports -Iexternal/skia/include/private -Iexternal/skia/include/svg -Iexternal/skia/include/utils -Iexternal/skia/include/utils/mac -Iexternal/skia/src/c -Iexternal/skia/src/codec -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/fonts -Iexternal/skia/src/gpu -Iexternal/skia/src/image -Iexternal/skia/src/images -Iexternal/skia/src/lazy -Iexternal/skia/src/opts -Iexternal/skia/src/pathops -Iexternal/skia/src/pdf -Iexternal/skia/src/ports -Iexternal/skia/src/sfnt -Iexternal/skia/src/shaders -Iexternal/skia/src/shaders/gradients -Iexternal/skia/src/sksl -Iexternal/skia/src/utils -Iexternal/skia/src/utils/win -Iexternal/skia/src/xml -Iexternal/skia/third_party/gif -Iexternal/skia/tools -Iexternal/skia/tools/debugger -Iexternal/skia/tools/flags -Iexternal/skia/tools/gpu -Iexternal/skia/tools/timer -Iexternal/skia/tools/trace/**/*.h"
    "${ANDROID_ROOT}/external/skia/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googletest/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include/**/*.h"
    "${ANDROID_ROOT}/external/jsoncpp/include/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/android/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/c/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/codec/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/config/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/core/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/effects/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/encode/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/gpu/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/gpu/gl/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/gpu/vk/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/pathops/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/ports/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/svg/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/utils/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/utils/mac/**/*.h"
    "${ANDROID_ROOT}/external/sfntly/cpp/src/**/*.h"
    "${ANDROID_ROOT}/external/webp/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/libs/EGL/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/external/dng_sdk/source/**/*.h"
    "${ANDROID_ROOT}/external/expat/lib/**/*.h"
    "${ANDROID_ROOT}/external/freetype/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libheif/include/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/i18n/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common/**/*.h"
    "${ANDROID_ROOT}/external/libjpeg-turbo/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativebase/include/**/*.h"
    "${ANDROID_ROOT}/external/piex/**/*.h"
    "${ANDROID_ROOT}/external/libpng/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/vulkan/include/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware/include/**/*.h"
    "${ANDROID_ROOT}/system/media/audio/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libsystem/include/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-exceptions")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-multichar")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-strict-aliasing")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstack-protector-strong")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ffunction-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fdata-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -funwind-tables")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wa,--noexecstack")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=format-security")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-short-enums")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -no-canonical-prefixes")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=pointer-to-int-cast")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=int-to-pointer-cast")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=implicit-function-declaration")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNDEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wstrict-aliasing=2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fmessage-length=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -W")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Winit-self")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wpointer-arith")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNDEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -UDEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fdebug-prefix-map=/proc/self/cwd=")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__compiler_offsetof=__builtin_offsetof")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=int-conversion")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-reserved-id-macro")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-format-pedantic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-command-line-argument")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fcolor-diagnostics")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-expansion-to-defined")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fdebug-prefix-map=$$PWD/=")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=return-type")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=non-virtual-dtor")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=address")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=sequence-point")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=date-time")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -nostdlibinc")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-multichar")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-strict-aliasing")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstack-protector-strong")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ffunction-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fdata-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -funwind-tables")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wa,--noexecstack")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=format-security")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-short-enums")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -no-canonical-prefixes")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=pointer-to-int-cast")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=int-to-pointer-cast")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=implicit-function-declaration")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNDEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wstrict-aliasing=2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fmessage-length=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -W")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Winit-self")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wpointer-arith")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNDEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -UDEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fdebug-prefix-map=/proc/self/cwd=")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__compiler_offsetof=__builtin_offsetof")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=int-conversion")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-reserved-id-macro")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-format-pedantic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-command-line-argument")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fcolor-diagnostics")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-expansion-to-defined")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fdebug-prefix-map=$$PWD/=")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=return-type")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=non-virtual-dtor")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=address")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=sequence-point")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=date-time")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -nostdlibinc")

# CFLAGS:
# Raw param [0] = '-Wno-unused-parameter'
# Raw param [1] = '-target aarch64-linux-android'
# Raw param [2] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [3] = '-fPIE'
# Raw param [4] = '-DGTEST_HAS_STD_STRING'
# Raw param [5] = '-DGTEST_OS_LINUX_ANDROID'
# Raw param [6] = '-D_USING_LIBCXX'
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-fPIE' became -fPIE
# FLAG '-DGTEST_HAS_STD_STRING' became -DGTEST_HAS_STD_STRING
# FLAG '-DGTEST_OS_LINUX_ANDROID' became -DGTEST_OS_LINUX_ANDROID
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_OS_LINUX_ANDROID")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_OS_LINUX_ANDROID")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_USING_LIBCXX")

# C ONLY FLAGS:
# Raw param [0] = '-std=gnu99'
# Raw param [1] = '${config.CommonGlobalConlyflags}'
# FLAG '-std=gnu99' became -std=gnu99
# variable ${config.CommonGlobalConlyflags} = ''
# Raw param [0] = ''
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=gnu99")

# CPP FLAGS:
# Raw param [0] = '-std=gnu++14'
# Raw param [1] = '${config.CommonClangGlobalCppflags}'
# Raw param [2] = '-fno-rtti'
# Raw param [3] = '${config.Arm64ClangCppflags}'
# FLAG '-std=gnu++14' became -std=gnu++14
# variable ${config.CommonClangGlobalCppflags} = '-Wsign-promo -Wno-inconsistent-missing-override -Wno-null-dereference -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS -Wno-thread-safety-negative'
# Raw param [0] = '-Wsign-promo'
# Raw param [1] = '-Wno-inconsistent-missing-override'
# Raw param [2] = '-Wno-null-dereference'
# Raw param [3] = '-D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS'
# Raw param [4] = '-Wno-thread-safety-negative'
# FLAG '-Wsign-promo' became -Wsign-promo
# FLAG '-Wno-inconsistent-missing-override' became -Wno-inconsistent-missing-override
# FLAG '-Wno-null-dereference' became -Wno-null-dereference
# FLAG '-D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS' became -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS
# FLAG '-Wno-thread-safety-negative' became -Wno-thread-safety-negative
# FLAG '-fno-rtti' became -fno-rtti
# variable ${config.Arm64ClangCppflags} = '-fvisibility-inlines-hidden'
# Raw param [0] = '-fvisibility-inlines-hidden'
# FLAG '-fvisibility-inlines-hidden' became -fvisibility-inlines-hidden
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++14")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-inconsistent-missing-override")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-dereference")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-rtti")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility-inlines-hidden")

# SYSTEM INCLUDE FLAGS:
# Raw param [0] = '${config.CommonGlobalIncludes}'
# Raw param [1] = '${config.Arm64IncludeFlags}'
# Raw param [2] = '${config.CommonNativehelperInclude}'
# variable ${config.CommonGlobalIncludes} = '-Isystem/core/include -Isystem/media/audio/include -Ihardware/libhardware/include -Ihardware/libhardware_legacy/include -Ihardware/ril/include -Ilibnativehelper/include -Iframeworks/native/include -Iframeworks/native/opengl/include -Iframeworks/av/include'
# Raw param [0] = '-Isystem/core/include'
# Raw param [1] = '-Isystem/media/audio/include'
# Raw param [2] = '-Ihardware/libhardware/include'
# Raw param [3] = '-Ihardware/libhardware_legacy/include'
# Raw param [4] = '-Ihardware/ril/include'
# Raw param [5] = '-Ilibnativehelper/include'
# Raw param [6] = '-Iframeworks/native/include'
# Raw param [7] = '-Iframeworks/native/opengl/include'
# Raw param [8] = '-Iframeworks/av/include'
# variable ${config.Arm64IncludeFlags} = '-isystem bionic/libc/arch-arm64/include -isystem bionic/libc/include -isystem bionic/libc/kernel/uapi -isystem bionic/libc/kernel/uapi/asm-arm64 -isystem bionic/libc/kernel/android/scsi -isystem bionic/libc/kernel/android/uapi'
# Raw param [0] = '-isystem'
# Raw param [1] = 'bionic/libc/arch-arm64/include'
# Raw param [2] = '-isystem'
# Raw param [3] = 'bionic/libc/include'
# Raw param [4] = '-isystem'
# Raw param [5] = 'bionic/libc/kernel/uapi'
# Raw param [6] = '-isystem'
# Raw param [7] = 'bionic/libc/kernel/uapi/asm-arm64'
# Raw param [8] = '-isystem'
# Raw param [9] = 'bionic/libc/kernel/android/scsi'
# Raw param [10] = '-isystem'
# Raw param [11] = 'bionic/libc/kernel/android/uapi'
# variable ${config.CommonNativehelperInclude} = '-Ilibnativehelper/include_deprecated'
# Raw param [0] = '-Ilibnativehelper/include_deprecated'
include_directories(SYSTEM 
    "${ANDROID_ROOT}/bionic/libc/arch-arm64/include"
    "${ANDROID_ROOT}/bionic/libc/include"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm64"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/scsi"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/uapi"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/bionic/libc/arch-arm64/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm64/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/scsi/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/uapi/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

include_directories( 
    "${ANDROID_ROOT}/system/core/include"
    "${ANDROID_ROOT}/system/media/audio/include"
    "${ANDROID_ROOT}/hardware/libhardware/include"
    "${ANDROID_ROOT}/hardware/libhardware_legacy/include"
    "${ANDROID_ROOT}/hardware/ril/include"
    "${ANDROID_ROOT}/libnativehelper/include"
    "${ANDROID_ROOT}/frameworks/native/include"
    "${ANDROID_ROOT}/frameworks/native/opengl/include"
    "${ANDROID_ROOT}/frameworks/av/include"
    "${ANDROID_ROOT}/libnativehelper/include_deprecated"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/system/core/include/**/*.h"
    "${ANDROID_ROOT}/system/media/audio/include/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware/include/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware_legacy/include/**/*.h"
    "${ANDROID_ROOT}/hardware/ril/include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/include_deprecated/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})


add_executable(skia_nanobench ${SOURCE_FILES})
