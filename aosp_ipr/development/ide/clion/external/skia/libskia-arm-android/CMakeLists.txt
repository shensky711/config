# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libskia)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/skia/src/android/SkBitmapRegionCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/android/SkBitmapRegionDecoder.cpp
    ${ANDROID_ROOT}/external/skia/src/c/sk_effects.cpp
    ${ANDROID_ROOT}/external/skia/src/c/sk_paint.cpp
    ${ANDROID_ROOT}/external/skia/src/c/sk_surface.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkAndroidCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkBmpBaseCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkBmpCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkBmpMaskCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkBmpRLECodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkBmpStandardCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/hwjpeg/HwJpegDecoderMgr.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkCodecImageGenerator.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkGifCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkHeifCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkIcoCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkJpegCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkJpegDecoderMgr.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkJpegUtility.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkMaskSwizzler.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkMasks.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkPngCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkRawAdapterCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkRawCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkSampledCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkSampler.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkStreamBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkSwizzler.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkWbmpCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkWebpAdapterCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkWebpCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkAAClip.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkATrace.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkAlphaRuns.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkAnalyticEdge.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkAnnotation.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkArenaAlloc.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkAutoPixmapStorage.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBBHFactory.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBigPicture.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBitmap.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBitmapCache.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBitmapController.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBitmapDevice.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBitmapProcState.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBitmapProcState_matrixProcs.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBitmapProvider.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBitmapScaler.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlendMode.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlitMask_D32.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlitRow_D32.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlitter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlitter_A8.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlitter_ARGB32.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlitter_RGB565.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlitter_Sprite.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlurImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkCachedData.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkCanvas.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkClipStack.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkClipStackDevice.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColor.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorLookUpTable.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorMatrixFilterRowMajor255.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorSpace.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorSpaceXform.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorSpaceXformCanvas.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorSpaceXformImageGenerator.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorSpaceXform_A2B.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorSpaceXformer.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorSpace_A2B.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorSpace_ICC.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorSpace_XYZ.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorTable.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkConvertPixels.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkConvolver.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkCpu.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkCubicClipper.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkData.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDataTable.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDebug.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDeque.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDevice.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDeviceLooper.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDeviceProfile.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDistanceFieldGen.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDither.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDocument.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDraw.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDrawLooper.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDraw_vertices.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDrawable.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkEdge.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkEdgeBuilder.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkEdgeClipper.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkExecutor.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkFlattenable.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkFlattenableSerialization.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkFont.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkFontDescriptor.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkFontLCDConfig.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkFontMgr.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkFontStream.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkFontStyle.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkGeometry.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkGlobalInitialization_core.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkGlyphCache.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkGpuBlurUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkGraphics.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkHalf.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkICC.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkImageFilterCache.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkImageGenerator.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkImageInfo.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkLatticeIter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkLights.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkLineClipper.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkLinearBitmapPipeline.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkLiteDL.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkLiteRecorder.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkLocalMatrixImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMD5.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMallocPixelRef.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMask.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMaskBlurFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMaskCache.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMaskFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMaskGamma.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMath.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMatrix.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMatrix44.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMatrixImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMetaData.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMiniRecorder.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMipMap.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkModeColorFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMultiPictureDraw.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkNormalFlatSource.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkNormalMapSource.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkNormalSource.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkOpts.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkOverdrawCanvas.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPaint.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPaintPriv.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPath.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPathEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPathMeasure.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPathRef.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPicture.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPictureAnalyzer.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPictureContentInfo.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPictureData.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPictureFlat.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPictureImageGenerator.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPicturePlayback.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPictureRecord.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPictureRecorder.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPixelRef.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPixmap.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPoint.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPoint3.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPtrRecorder.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkQuadClipper.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRRect.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRTree.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRWBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRasterClip.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRasterPipeline.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRasterPipelineBlitter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRasterizer.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkReadBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRecord.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRecordDraw.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRecordOpts.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRecordedDrawable.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRecorder.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRecords.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRect.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRefDict.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRegion.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRegion_path.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkResourceCache.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSRGB.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkScalar.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkScalerContext.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkScan.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkScan_AAAPath.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkScan_AntiPath.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkScan_Antihair.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkScan_Hairline.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkScan_Path.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSemaphore.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSharedMutex.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSpecialImage.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSpecialSurface.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSpinlock.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSpriteBlitter_ARGB32.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSpriteBlitter_RGB565.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkStream.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkString.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkStringUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkStroke.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkStrokeRec.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkStrokerPriv.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSwizzle.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkTLS.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkTSearch.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkTaskGroup.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkTextBlob.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkThreadID.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkTime.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkTypeface.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkTypefaceCache.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkUnPreMultiply.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkValidatingReadBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkVertState.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkVertices.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkWriteBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkWriter32.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkXfermode.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkXfermodeInterpretation.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkYUVPlanesCache.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/GrAlphaThresholdFragmentProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/GrCircleBlurFragmentProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/Sk1DPathEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/Sk2DPathEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkAlphaThresholdFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkArcToPathEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkArithmeticImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkBlurMask.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkBlurMaskFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkColorFilterImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkColorMatrix.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkColorMatrixFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkComposeImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkCornerPathEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkDashPathEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkDiscretePathEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkDisplacementMapEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkDropShadowImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkEmbossMask.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkEmbossMaskFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkHighContrastFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkImageSource.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkLayerDrawLooper.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkLayerRasterizer.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkLightingImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkLumaColorFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkMagnifierImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkMatrixConvolutionImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkMergeImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkMorphologyImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkOffsetImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkOverdrawColorFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkPackBits.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkPaintFlagsDrawFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkPaintImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkPictureImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkRRectsGaussianEdgeMaskFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkTableColorFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkTableMaskFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkTileImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkXfermodeImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/fonts/SkRandomScalerContext.cpp
    ${ANDROID_ROOT}/external/skia/src/fonts/SkTestScalerContext.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrAHardwareBufferImageGenerator.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrAuditTrail.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrBackendSurface.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrBackendTextureImageGenerator.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrBitmapTextureMaker.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrBlend.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrBlurUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrBufferAllocPool.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrCaps.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrClipStackClip.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrColorSpaceXform.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrContext.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrDefaultGeoProcFactory.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrDistanceFieldGenFromVector.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrDrawOpAtlas.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrDrawOpTest.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrDrawingManager.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrFixedClip.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrFragmentProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrGpu.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrGpuCommandBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrGpuFactory.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrGpuResource.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrGpuResourceRef.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrImageTextureMaker.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrMemoryPool.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrOnFlushResourceProvider.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrOpFlushState.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrOpList.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrPaint.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrPath.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrPathProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrPathRange.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrPathRenderer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrPathRendererChain.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrPathRendering.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrPathRenderingRenderTargetContext.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrPathUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrPipeline.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrPrimitiveProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrProcessorAnalysis.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrProcessorSet.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrProcessorUnitTest.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrProgramDesc.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrRectanizer_pow2.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrRectanizer_skyline.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrReducedClip.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrRenderTarget.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrRenderTargetContext.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrRenderTargetOpList.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrRenderTargetProxy.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrResourceAllocator.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrResourceCache.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrResourceProvider.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrSKSLPrettyPrint.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrSWMaskHelper.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrShaderCaps.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrShaderVar.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrShape.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrSoftwarePathRenderer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrStencilAttachment.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrStencilSettings.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrStyle.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrSurface.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrSurfaceContext.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrSurfaceProxy.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrTessellator.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrTestUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrTexture.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrTextureAdjuster.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrTextureContext.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrTextureMaker.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrTextureOpList.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrTextureProducer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrTextureProxy.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrTextureRenderTargetProxy.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrTraceMarker.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrXferProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/GrYUVProvider.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/SkGpuDevice.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/SkGpuDevice_drawTexture.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/SkGr.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ccpr/GrCCPRAtlas.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ccpr/GrCCPRCoverageOpsBuilder.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ccpr/GrCCPRCoverageProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ccpr/GrCCPRCubicProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ccpr/GrCCPRPathProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ccpr/GrCCPRQuadraticProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ccpr/GrCCPRTriangleProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ccpr/GrCoverageCountingPathRenderer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrBezierEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrBicubicEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrBitmapTextGeoProc.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrBlurredEdgeFragmentProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrCircleEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrConfigConversionEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrConstColorProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrConvexPolyEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrCoverageSetOpXP.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrCustomXfermode.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrDisableColorXP.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrDistanceFieldGeoProc.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrDitherEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrEllipseEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrGaussianConvolutionFragmentProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrMatrixConvolutionEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrNonlinearColorSpaceXformEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrOvalEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrPorterDuffXferProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrRRectEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrSRGBEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrShadowGeoProc.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrSimpleTextureEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrSingleTextureEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrTextureDomain.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrTextureStripAtlas.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrXfermodeFragmentProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/effects/GrYUVEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLAssembleInterface.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLCaps.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLContext.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLCreateNullInterface.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLDefaultInterface_native.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLExtensions.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLGLSL.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLGpu.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLGpuProgramCache.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLInterface.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLPath.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLPathRange.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLPathRendering.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLProgram.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLProgramDataManager.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLRenderTarget.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLSemaphore.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLStencilAttachment.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLTestInterface.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLTexture.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLTextureRenderTarget.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLUniformHandler.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLUtil.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLVaryingHandler.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/GrGLVertexArray.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/android/GrGLCreateNativeInterface_android.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/builders/GrGLProgramBuilder.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/gl/builders/GrGLShaderStringBuilder.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/glsl/GrGLSL.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/glsl/GrGLSLBlend.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/glsl/GrGLSLFragmentProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/glsl/GrGLSLFragmentShaderBuilder.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/glsl/GrGLSLGeometryProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/glsl/GrGLSLGeometryShaderBuilder.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/glsl/GrGLSLPrimitiveProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/glsl/GrGLSLProgramBuilder.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/glsl/GrGLSLProgramDataManager.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/glsl/GrGLSLShaderBuilder.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/glsl/GrGLSLUtil.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/glsl/GrGLSLVarying.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/glsl/GrGLSLVertexShaderBuilder.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/glsl/GrGLSLXferProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/instanced/GLInstancedRendering.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/instanced/InstanceProcessor.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/instanced/InstancedOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/instanced/InstancedRendering.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/mock/GrMockGpu.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrAAConvexPathRenderer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrAAConvexTessellator.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrAAFillRectOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrAAHairLinePathRenderer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrAALinearizingConvexPathRenderer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrAAStrokeRectOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrAtlasTextOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrClearOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrCopySurfaceOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrDashLinePathRenderer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrDashOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrDefaultPathRenderer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrDrawAtlasOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrDrawOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrDrawPathOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrDrawVerticesOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrLatticeOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrMSAAPathRenderer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrMeshDrawOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrNonAAFillRectOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrNonAAStrokeRectOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrOvalOpFactory.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrRegionOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrSemaphoreOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrShadowRRectOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrSimpleMeshDrawOpHelper.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrSmallPathRenderer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrStencilAndCoverPathRenderer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrStencilPathOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/ops/GrTessellatingPathRenderer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/text/GrAtlasGlyphCache.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/text/GrAtlasTextBlob.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/text/GrAtlasTextBlob_regenInOp.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/text/GrAtlasTextContext.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/text/GrDistanceFieldAdjustTable.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/text/GrStencilAndCoverTextContext.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/text/GrTextBlobCache.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/text/GrTextUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkBackendContext.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkBufferView.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkCaps.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkCommandBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkCopyManager.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkCopyPipeline.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkDescriptorPool.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkDescriptorSet.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkDescriptorSetManager.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkExtensions.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkFramebuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkGpu.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkGpuCommandBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkImage.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkImageView.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkIndexBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkInterface.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkMemory.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkPipeline.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkPipelineState.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkPipelineStateBuilder.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkPipelineStateCache.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkPipelineStateDataManager.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkRenderPass.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkRenderTarget.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkResourceProvider.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkSampler.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkSemaphore.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkStencilAttachment.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkTexelBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkTexture.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkTextureRenderTarget.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkTransferBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkUniformBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkUniformHandler.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkUtil.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkVaryingHandler.cpp
    ${ANDROID_ROOT}/external/skia/src/gpu/vk/GrVkVertexBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/image/SkImage.cpp
    ${ANDROID_ROOT}/external/skia/src/image/SkImage_Gpu.cpp
    ${ANDROID_ROOT}/external/skia/src/image/SkImage_Lazy.cpp
    ${ANDROID_ROOT}/external/skia/src/image/SkImage_Raster.cpp
    ${ANDROID_ROOT}/external/skia/src/image/SkSurface.cpp
    ${ANDROID_ROOT}/external/skia/src/image/SkSurface_Gpu.cpp
    ${ANDROID_ROOT}/external/skia/src/image/SkSurface_Raster.cpp
    ${ANDROID_ROOT}/external/skia/src/images/SkImageEncoder.cpp
    ${ANDROID_ROOT}/external/skia/src/images/SkJPEGWriteUtility.cpp
    ${ANDROID_ROOT}/external/skia/src/images/SkJpegEncoder.cpp
    ${ANDROID_ROOT}/external/skia/src/images/SkPngEncoder.cpp
    ${ANDROID_ROOT}/external/skia/src/images/SkWebpEncoder.cpp
    ${ANDROID_ROOT}/external/skia/src/jumper/SkJumper.cpp
    ${ANDROID_ROOT}/external/skia/src/jumper/SkJumper_generated.S
    ${ANDROID_ROOT}/external/skia/src/jumper/SkJumper_stages.cpp
    ${ANDROID_ROOT}/external/skia/src/lazy/SkDiscardableMemoryPool.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkAddIntersections.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkDConicLineIntersection.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkDCubicLineIntersection.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkDCubicToQuads.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkDLineIntersection.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkDQuadLineIntersection.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkIntersections.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkOpAngle.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkOpBuilder.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkOpCoincidence.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkOpContour.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkOpCubicHull.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkOpEdgeBuilder.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkOpSegment.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkOpSpan.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsCommon.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsConic.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsCubic.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsCurve.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsDebug.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsLine.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsOp.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsPoint.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsQuad.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsRect.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsSimplify.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsTSect.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsTightBounds.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsTypes.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsWinding.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathWriter.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkReduceOrder.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkDeflate.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkJpegInfo.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkKeyedImage.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFBitmap.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFCanon.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFConvertType1FontStream.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFDevice.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFDocument.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFFont.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFFormXObject.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFGradientShader.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFGraphicState.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFMakeCIDGlyphWidthsArray.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFMakeToUnicodeCmap.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFMetadata.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFResourceDict.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFShader.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFTypes.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/pipe/SkPipeCanvas.cpp
    ${ANDROID_ROOT}/external/skia/src/pipe/SkPipeReader.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkDebug_android.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkDiscardableMemory_none.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkFontHost_FreeType.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkFontHost_FreeType_common.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkFontMgr_android.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkFontMgr_android_factory.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkFontMgr_android_parser.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkGlobalInitialization_default.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkImageGenerator_skia.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkMemory_malloc.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkOSFile_posix.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkOSFile_stdio.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkOSLibrary_posix.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkTLS_pthread.cpp
    ${ANDROID_ROOT}/external/skia/src/sfnt/SkOTTable_name.cpp
    ${ANDROID_ROOT}/external/skia/src/sfnt/SkOTUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkBitmapProcShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkColorFilterShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkColorShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkComposeShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkImageShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkLightingShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkLocalMatrixShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkPerlinNoiseShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkPictureShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/gradients/Sk4fGradientBase.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/gradients/Sk4fLinearGradient.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/gradients/SkClampRange.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/gradients/SkGradientBitmapCache.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/gradients/SkGradientShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/gradients/SkLinearGradient.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/gradients/SkRadialGradient.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/gradients/SkSweepGradient.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/gradients/SkTwoPointConicalGradient.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/gradients/SkTwoPointConicalGradient_gpu.cpp
    ${ANDROID_ROOT}/external/skia/src/sksl/SkSLCFGGenerator.cpp
    ${ANDROID_ROOT}/external/skia/src/sksl/SkSLCPPCodeGenerator.cpp
    ${ANDROID_ROOT}/external/skia/src/sksl/SkSLCompiler.cpp
    ${ANDROID_ROOT}/external/skia/src/sksl/SkSLGLSLCodeGenerator.cpp
    ${ANDROID_ROOT}/external/skia/src/sksl/SkSLHCodeGenerator.cpp
    ${ANDROID_ROOT}/external/skia/src/sksl/SkSLIRGenerator.cpp
    ${ANDROID_ROOT}/external/skia/src/sksl/SkSLParser.cpp
    ${ANDROID_ROOT}/external/skia/src/sksl/SkSLSPIRVCodeGenerator.cpp
    ${ANDROID_ROOT}/external/skia/src/sksl/SkSLString.cpp
    ${ANDROID_ROOT}/external/skia/src/sksl/SkSLUtil.cpp
    ${ANDROID_ROOT}/external/skia/src/sksl/ir/SkSLSetting.cpp
    ${ANDROID_ROOT}/external/skia/src/sksl/ir/SkSLSymbolTable.cpp
    ${ANDROID_ROOT}/external/skia/src/sksl/ir/SkSLType.cpp
    ${ANDROID_ROOT}/external/skia/src/sksl/lex.layout.cpp
    ${ANDROID_ROOT}/external/skia/src/svg/SkSVGCanvas.cpp
    ${ANDROID_ROOT}/external/skia/src/svg/SkSVGDevice.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkBase64.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkBitmapSourceDeserializer.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkCamera.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkCanvasStack.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkCanvasStateUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkCurveMeasure.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkDashPath.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkDeferredCanvas.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkDumpCanvas.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkEventTracer.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkFrontBufferedStream.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkInsetConvexPolygon.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkInterpolator.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkMatrix22.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkMultiPictureDocument.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkNWayCanvas.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkNullCanvas.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkOSPath.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkPaintFilterCanvas.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkParse.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkParseColor.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkParsePath.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkPatchUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkShadowTessellator.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkShadowUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkTextBox.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkThreadUtils_pthread.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkThreadUtils_win.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkWhitelistTypefaces.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/mac/SkCreateCGImageRef.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/mac/SkStream_mac.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/win/SkAutoCoInitialize.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/win/SkDWrite.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/win/SkDWriteFontFileStream.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/win/SkDWriteGeometrySink.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/win/SkHRESULT.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/win/SkIStream.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/win/SkWGL_win.cpp
    ${ANDROID_ROOT}/external/skia/src/xml/SkDOM.cpp
    ${ANDROID_ROOT}/external/skia/src/xml/SkXMLParser.cpp
    ${ANDROID_ROOT}/external/skia/src/xml/SkXMLWriter.cpp
    ${ANDROID_ROOT}/external/skia/src/xps/SkXPSDevice.cpp
    ${ANDROID_ROOT}/external/skia/src/xps/SkXPSDocument.cpp
    ${ANDROID_ROOT}/external/skia/third_party/gif/SkGifImageReader.cpp
    ${ANDROID_ROOT}/external/skia/src/opts/SkBitmapProcState_opts_none.cpp
    ${ANDROID_ROOT}/external/skia/src/opts/SkBlitMask_opts_arm.cpp
    ${ANDROID_ROOT}/external/skia/src/opts/SkBlitRow_opts_arm.cpp
    ${ANDROID_ROOT}/external/skia/src/opts/SkBitmapProcState_arm_neon.cpp
    ${ANDROID_ROOT}/external/skia/src/opts/SkBitmapProcState_matrixProcs_neon.cpp
    ${ANDROID_ROOT}/external/skia/src/opts/SkBlitMask_opts_arm_neon.cpp
    ${ANDROID_ROOT}/external/skia/src/opts/SkBlitRow_opts_arm_neon.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/skia/include/android -Iexternal/skia/include/c -Iexternal/skia/include/codec -Iexternal/skia/include/config -Iexternal/skia/include/core -Iexternal/skia/include/effects -Iexternal/skia/include/encode -Iexternal/skia/include/gpu -Iexternal/skia/include/gpu/gl -Iexternal/skia/include/gpu/vk -Iexternal/skia/include/pathops -Iexternal/skia/include/ports -Iexternal/skia/include/svg -Iexternal/skia/include/utils -Iexternal/skia/include/utils/mac'
# Raw param [1] = '-Iexternal/skia/include/android -Iexternal/skia/include/c -Iexternal/skia/include/codec -Iexternal/skia/include/config -Iexternal/skia/include/core -Iexternal/skia/include/effects -Iexternal/skia/include/encode -Iexternal/skia/include/gpu -Iexternal/skia/include/gpu/gl -Iexternal/skia/include/gpu/vk -Iexternal/skia/include/pathops -Iexternal/skia/include/ports -Iexternal/skia/include/private -Iexternal/skia/include/svg -Iexternal/skia/include/utils -Iexternal/skia/include/utils/mac -Iexternal/skia/src/c -Iexternal/skia/src/codec -Iexternal/skia/src/codec/hwjpeg -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/fonts -Iexternal/skia/src/gpu -Iexternal/skia/src/image -Iexternal/skia/src/images -Iexternal/skia/src/lazy -Iexternal/skia/src/opts -Iexternal/skia/src/pathops -Iexternal/skia/src/pdf -Iexternal/skia/src/ports -Iexternal/skia/src/sfnt -Iexternal/skia/src/shaders -Iexternal/skia/src/shaders/gradients -Iexternal/skia/src/sksl -Iexternal/skia/src/utils -Iexternal/skia/src/utils/win -Iexternal/skia/src/xml -Iexternal/skia/third_party/gif'
# Raw param [2] = '-Isystem/core/include/utils'
# Raw param [3] = '-Iexternal/skia'
# Raw param [4] = '${config.ArmClangThumbCflags}'
# Raw param [5] = '${config.ArmClangCflags}'
# Raw param [6] = '${config.CommonClangGlobalCflags}'
# Raw param [7] = '${config.DeviceClangGlobalCflags}'
# Raw param [8] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv7ANeonCflags} ${config.ArmClangGenericCflags}'
# Raw param [9] = '-Iframeworks/native/libs/arect/include'
# Raw param [10] = '-Iexternal/sfntly/cpp/src'
# Raw param [11] = '-Iexternal/webp/include'
# Raw param [12] = '-Iexternal/libcxx/include'
# Raw param [13] = '-Iexternal/libcxxabi/include'
# Raw param [14] = '-Iframeworks/native/opengl/libs/EGL/include'
# Raw param [15] = '-Iframeworks/native/opengl/include'
# Raw param [16] = '-Iexternal/dng_sdk/source'
# Raw param [17] = '-Iexternal/expat/lib'
# Raw param [18] = '-Iexternal/freetype/include'
# Raw param [19] = '-Iframeworks/av/media/libheif/include'
# Raw param [20] = '-Iexternal/icu/icu4c/source/i18n'
# Raw param [21] = '-Iexternal/icu/icu4c/source/common'
# Raw param [22] = '-Iexternal/libjpeg-turbo'
# Raw param [23] = '-Isystem/core/liblog/include'
# Raw param [24] = '-Iexternal/piex'
# Raw param [25] = '-Iexternal/libpng'
# Raw param [26] = '-Iframeworks/native/vulkan/include'
# Raw param [27] = '-Isystem/core/libcutils/include'
# Raw param [28] = '-Ihardware/libhardware/include'
# Raw param [29] = '-Isystem/media/audio/include'
# Raw param [30] = '-Isystem/core/libsystem/include'
# Raw param [31] = '-Iexternal/zlib'
# Raw param [32] = '-Iframeworks/native/libs/nativewindow/include'
# Raw param [33] = '-Iframeworks/native/libs/nativebase/include'
# variable ${config.ArmClangThumbCflags} = '-mthumb -Os -fomit-frame-pointer -fno-strict-aliasing'
# Raw param [0] = '-mthumb'
# Raw param [1] = '-Os'
# Raw param [2] = '-fomit-frame-pointer'
# Raw param [3] = '-fno-strict-aliasing'
# FLAG '-mthumb' became -mthumb
# FLAG '-Os' became -Os
# FLAG '-fomit-frame-pointer' became -fomit-frame-pointer
# FLAG '-fno-strict-aliasing' became -fno-strict-aliasing
# variable ${config.ArmClangCflags} = '-fno-exceptions -Wno-multichar -ffunction-sections -fdata-sections -funwind-tables -fstack-protector-strong -Wa,--noexecstack -Werror=format-security -D_FORTIFY_SOURCE=2 -fno-short-enums -no-canonical-prefixes -DNDEBUG -g -Wstrict-aliasing=2'
# Raw param [0] = '-fno-exceptions'
# Raw param [1] = '-Wno-multichar'
# Raw param [2] = '-ffunction-sections'
# Raw param [3] = '-fdata-sections'
# Raw param [4] = '-funwind-tables'
# Raw param [5] = '-fstack-protector-strong'
# Raw param [6] = '-Wa,--noexecstack'
# Raw param [7] = '-Werror=format-security'
# Raw param [8] = '-D_FORTIFY_SOURCE=2'
# Raw param [9] = '-fno-short-enums'
# Raw param [10] = '-no-canonical-prefixes'
# Raw param [11] = '-DNDEBUG'
# Raw param [12] = '-g'
# Raw param [13] = '-Wstrict-aliasing=2'
# FLAG '-fno-exceptions' became -fno-exceptions
# FLAG '-Wno-multichar' became -Wno-multichar
# FLAG '-ffunction-sections' became -ffunction-sections
# FLAG '-fdata-sections' became -fdata-sections
# FLAG '-funwind-tables' became -funwind-tables
# FLAG '-fstack-protector-strong' became -fstack-protector-strong
# FLAG '-Wa,--noexecstack' became -Wa,--noexecstack
# FLAG '-Werror=format-security' became -Werror=format-security
# FLAG '-D_FORTIFY_SOURCE=2' became -D_FORTIFY_SOURCE=2
# FLAG '-fno-short-enums' became -fno-short-enums
# FLAG '-no-canonical-prefixes' became -no-canonical-prefixes
# FLAG '-DNDEBUG' became -DNDEBUG
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
# variable ${config.ArmToolchainClangCflags} ${config.ArmClangArmv7ANeonCflags} ${config.ArmClangGenericCflags} = '-msoft-float -mfloat-abi=softfp -mfpu=neon -march=armv7-a'
# Raw param [0] = '-msoft-float'
# Raw param [1] = '-mfloat-abi=softfp'
# Raw param [2] = '-mfpu=neon'
# Raw param [3] = '-march=armv7-a'
# FLAG '-msoft-float' became -msoft-float
# FLAG '-mfloat-abi=softfp' became -mfloat-abi=softfp
# FLAG '-mfpu=neon' became -mfpu=neon
# FLAG '-march=armv7-a' became -march=armv7-a
include_directories( 
    "${ANDROID_ROOT}/external/skia/include/android -Iexternal/skia/include/c -Iexternal/skia/include/codec -Iexternal/skia/include/config -Iexternal/skia/include/core -Iexternal/skia/include/effects -Iexternal/skia/include/encode -Iexternal/skia/include/gpu -Iexternal/skia/include/gpu/gl -Iexternal/skia/include/gpu/vk -Iexternal/skia/include/pathops -Iexternal/skia/include/ports -Iexternal/skia/include/svg -Iexternal/skia/include/utils -Iexternal/skia/include/utils/mac"
    "${ANDROID_ROOT}/external/skia/include/android -Iexternal/skia/include/c -Iexternal/skia/include/codec -Iexternal/skia/include/config -Iexternal/skia/include/core -Iexternal/skia/include/effects -Iexternal/skia/include/encode -Iexternal/skia/include/gpu -Iexternal/skia/include/gpu/gl -Iexternal/skia/include/gpu/vk -Iexternal/skia/include/pathops -Iexternal/skia/include/ports -Iexternal/skia/include/private -Iexternal/skia/include/svg -Iexternal/skia/include/utils -Iexternal/skia/include/utils/mac -Iexternal/skia/src/c -Iexternal/skia/src/codec -Iexternal/skia/src/codec/hwjpeg -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/fonts -Iexternal/skia/src/gpu -Iexternal/skia/src/image -Iexternal/skia/src/images -Iexternal/skia/src/lazy -Iexternal/skia/src/opts -Iexternal/skia/src/pathops -Iexternal/skia/src/pdf -Iexternal/skia/src/ports -Iexternal/skia/src/sfnt -Iexternal/skia/src/shaders -Iexternal/skia/src/shaders/gradients -Iexternal/skia/src/sksl -Iexternal/skia/src/utils -Iexternal/skia/src/utils/win -Iexternal/skia/src/xml -Iexternal/skia/third_party/gif"
    "${ANDROID_ROOT}/system/core/include/utils"
    "${ANDROID_ROOT}/external/skia"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include"
    "${ANDROID_ROOT}/external/sfntly/cpp/src"
    "${ANDROID_ROOT}/external/webp/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/frameworks/native/opengl/libs/EGL/include"
    "${ANDROID_ROOT}/frameworks/native/opengl/include"
    "${ANDROID_ROOT}/external/dng_sdk/source"
    "${ANDROID_ROOT}/external/expat/lib"
    "${ANDROID_ROOT}/external/freetype/include"
    "${ANDROID_ROOT}/frameworks/av/media/libheif/include"
    "${ANDROID_ROOT}/external/icu/icu4c/source/i18n"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common"
    "${ANDROID_ROOT}/external/libjpeg-turbo"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/external/piex"
    "${ANDROID_ROOT}/external/libpng"
    "${ANDROID_ROOT}/frameworks/native/vulkan/include"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/hardware/libhardware/include"
    "${ANDROID_ROOT}/system/media/audio/include"
    "${ANDROID_ROOT}/system/core/libsystem/include"
    "${ANDROID_ROOT}/external/zlib"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include"
    "${ANDROID_ROOT}/frameworks/native/libs/nativebase/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/skia/include/android -Iexternal/skia/include/c -Iexternal/skia/include/codec -Iexternal/skia/include/config -Iexternal/skia/include/core -Iexternal/skia/include/effects -Iexternal/skia/include/encode -Iexternal/skia/include/gpu -Iexternal/skia/include/gpu/gl -Iexternal/skia/include/gpu/vk -Iexternal/skia/include/pathops -Iexternal/skia/include/ports -Iexternal/skia/include/svg -Iexternal/skia/include/utils -Iexternal/skia/include/utils/mac/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/android -Iexternal/skia/include/c -Iexternal/skia/include/codec -Iexternal/skia/include/config -Iexternal/skia/include/core -Iexternal/skia/include/effects -Iexternal/skia/include/encode -Iexternal/skia/include/gpu -Iexternal/skia/include/gpu/gl -Iexternal/skia/include/gpu/vk -Iexternal/skia/include/pathops -Iexternal/skia/include/ports -Iexternal/skia/include/private -Iexternal/skia/include/svg -Iexternal/skia/include/utils -Iexternal/skia/include/utils/mac -Iexternal/skia/src/c -Iexternal/skia/src/codec -Iexternal/skia/src/codec/hwjpeg -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/fonts -Iexternal/skia/src/gpu -Iexternal/skia/src/image -Iexternal/skia/src/images -Iexternal/skia/src/lazy -Iexternal/skia/src/opts -Iexternal/skia/src/pathops -Iexternal/skia/src/pdf -Iexternal/skia/src/ports -Iexternal/skia/src/sfnt -Iexternal/skia/src/shaders -Iexternal/skia/src/shaders/gradients -Iexternal/skia/src/sksl -Iexternal/skia/src/utils -Iexternal/skia/src/utils/win -Iexternal/skia/src/xml -Iexternal/skia/third_party/gif/**/*.h"
    "${ANDROID_ROOT}/system/core/include/utils/**/*.h"
    "${ANDROID_ROOT}/external/skia/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include/**/*.h"
    "${ANDROID_ROOT}/external/sfntly/cpp/src/**/*.h"
    "${ANDROID_ROOT}/external/webp/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/libs/EGL/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/include/**/*.h"
    "${ANDROID_ROOT}/external/dng_sdk/source/**/*.h"
    "${ANDROID_ROOT}/external/expat/lib/**/*.h"
    "${ANDROID_ROOT}/external/freetype/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libheif/include/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/i18n/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common/**/*.h"
    "${ANDROID_ROOT}/external/libjpeg-turbo/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/external/piex/**/*.h"
    "${ANDROID_ROOT}/external/libpng/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/vulkan/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware/include/**/*.h"
    "${ANDROID_ROOT}/system/media/audio/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libsystem/include/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativebase/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mthumb")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Os")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fomit-frame-pointer")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-strict-aliasing")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-exceptions")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-multichar")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ffunction-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fdata-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -funwind-tables")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstack-protector-strong")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wa,--noexecstack")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=format-security")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-short-enums")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -no-canonical-prefixes")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNDEBUG")
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -msoft-float")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mfloat-abi=softfp")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mfpu=neon")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -march=armv7-a")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mthumb")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Os")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fomit-frame-pointer")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-strict-aliasing")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-multichar")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ffunction-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fdata-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -funwind-tables")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstack-protector-strong")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wa,--noexecstack")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=format-security")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-short-enums")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -no-canonical-prefixes")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNDEBUG")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -msoft-float")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mfloat-abi=softfp")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mfpu=neon")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -march=armv7-a")

# CFLAGS:
# Raw param [0] = '-fexceptions'
# Raw param [1] = '-Wno-unused-parameter'
# Raw param [2] = '-U_FORTIFY_SOURCE'
# Raw param [3] = '-D_FORTIFY_SOURCE=1'
# Raw param [4] = '-DSKIA_IMPLEMENTATION=1'
# Raw param [5] = '-DATRACE_TAG=ATRACE_TAG_VIEW'
# Raw param [6] = '-target arm-linux-androideabi'
# Raw param [7] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [8] = '-fPIC'
# Raw param [9] = '-D_USING_LIBCXX'
# FLAG '-fexceptions' became -fexceptions
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-U_FORTIFY_SOURCE' became -U_FORTIFY_SOURCE
# FLAG '-D_FORTIFY_SOURCE=1' became -D_FORTIFY_SOURCE=1
# FLAG '-DSKIA_IMPLEMENTATION=1' became -DSKIA_IMPLEMENTATION=1
# FLAG '-DATRACE_TAG=ATRACE_TAG_VIEW' became -DATRACE_TAG=ATRACE_TAG_VIEW
# FLAG '-target arm-linux-androideabi' became -target arm-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fexceptions")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -U_FORTIFY_SOURCE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FORTIFY_SOURCE=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSKIA_IMPLEMENTATION=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DATRACE_TAG=ATRACE_TAG_VIEW")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target arm-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fexceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -U_FORTIFY_SOURCE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FORTIFY_SOURCE=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSKIA_IMPLEMENTATION=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DATRACE_TAG=ATRACE_TAG_VIEW")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target arm-linux-androideabi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
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
# Raw param [3] = '${config.ArmClangCppflags}'
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
# variable ${config.ArmClangCppflags} = '-fvisibility-inlines-hidden'
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
# Raw param [1] = '${config.ArmIncludeFlags}'
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
# variable ${config.ArmIncludeFlags} = '-isystem bionic/libc/arch-arm/include -isystem bionic/libc/include -isystem bionic/libc/kernel/uapi -isystem bionic/libc/kernel/uapi/asm-arm -isystem bionic/libc/kernel/android/scsi -isystem bionic/libc/kernel/android/uapi'
# Raw param [0] = '-isystem'
# Raw param [1] = 'bionic/libc/arch-arm/include'
# Raw param [2] = '-isystem'
# Raw param [3] = 'bionic/libc/include'
# Raw param [4] = '-isystem'
# Raw param [5] = 'bionic/libc/kernel/uapi'
# Raw param [6] = '-isystem'
# Raw param [7] = 'bionic/libc/kernel/uapi/asm-arm'
# Raw param [8] = '-isystem'
# Raw param [9] = 'bionic/libc/kernel/android/scsi'
# Raw param [10] = '-isystem'
# Raw param [11] = 'bionic/libc/kernel/android/uapi'
# variable ${config.CommonNativehelperInclude} = '-Ilibnativehelper/include_deprecated'
# Raw param [0] = '-Ilibnativehelper/include_deprecated'
include_directories(SYSTEM 
    "${ANDROID_ROOT}/bionic/libc/arch-arm/include"
    "${ANDROID_ROOT}/bionic/libc/include"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/scsi"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/uapi"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/bionic/libc/arch-arm/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm/**/*.h"
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


add_executable(libskia ${SOURCE_FILES})
