# image_processing

## ch1

### technique

digital image enhancement - equalization, sharpening, noise elimination

digital image restoration

digital image transformation - fourier, discrete cosine, wavelet

digital image analysis

digital image understanding

digital image compression - lossless, loss

### algorithm

point processing - arithmetic, logical operation

area processing - bluring, sharpening

geometric processing - scale, rotation, translation

frame processing

application field - composition, morphing, warping, x-ray, 초음파, mri, ct, machine vision, biometrics, watermarking, dip, pdf

## ch2

contrast - 명도 대비

color model - rgb, cmyk, hsi, ycbcr, yiq, yuv

sampling theory

spatial resolution, intensity resolution, color resolution

## ch3

영상 파일 포맷의 종류 - BMP, JPEG, RAW, GIF, PSD, TIFF 등

BMP, JPEG 파일 포맷은 영상의 색상 정보, 해상도 등을 알 수 있는 header 정보가 있음.

RAW 파일 포맷은 header 정보 없이 data만으로 구성.

down sampling - 디지털 영상 축소

up sampling - 디지털 영상 확대 (interpolation)

quantization - 픽셀의 밝기나 색상값을 몇단계 양자화된 표본값으로 결정 (quantization bits)

## ch4 point processing

contrast, clamping, wraping

### arithmetic operation

sum constant, sub constant, mul constant, div constant

### logical operation

and operate(mask), or operate(selective-set), xor operate(compare), not(negative transform)

null transform, intensity contrast stretch, intensity contrast compress, posterizing

gamma correction, binarization, stress transform

## ch5 histogram

histogram stretching, end in search, histogram equalization, histogram specification

## ch6 convolution processing

embossing, blurring(low pass filter), sharpening(high pass filter), edge detection, noise elimination

zero padding, smoothing, gaussian filter, unsharp masking, high-boost filter

## ch7 edge detection

homogeneity operator, difference operator, threshold, shift difference, diff_operator_hor

roberts, sobel, prewitt

compass gradient operator, laplacian, log(laplacian of gaussian), dog(difference of gaussians)

color image edge detection

## ch8 geometric processing

forward, backward mapping, shift, transformation, matching, overlap, hole

interpolation - nearest neighbor, bilinear, cubic convolution, b-spline

### scaling

magnification, scaling up, zooming, up samling

minification, scaling down, decimation, down sampling

### linear geometric transformation

translation, rotation, scaling

### nonlinear geometric transformation

warping, morphing

aliasing - blurring으로 해결

median sub sampling, mean sub sampling

## ch9

translation, mirroring hor, mirroring ver, rotation

warping, rubber sheet transform, mesh warping

morphing, cross-dissolve, transfer morphing, distorted morphing

## ch10 frame processing

combination processing, composition processing

frame sum, frame sub, frame mul, frame div

average operation

frame and, frame or, frame comb

frame to frame prediction, motion prediction, motion compensation

intra picture, predicted pictures, bi-directional predicted pictures

## ch11 morphology

이동, 반사

dilation, erosion

binary erosion, binary dilation

열림 - erosion -> dilation

닫힘(채움) - dilation -> erosion

skeletonization

gray erosion, gray dilation

## ch12 filter

finite impulse response, infinite impulse response, convolution

### spatial filtering

low pass filter, gaussian filter

high pass filter, sharpening filter

### linear spatial filtering noise elimination

mean filter

### nonlinear spatial filtering noise elimination

median filter, weighted median filter

max filter, min filter

opening filter - min -> max

closing filter - max -> min

## ch13 image transformation

### fourier transform, discrete fourier transformation, fast fourier transformation

scrambling, butterfly, fft, ifft

spectrum, shuffling

### discrete cosine transform

convolution theorem

lpf frequency, hpf frequency

### wavelet transformation, daubechies, octave tree structure

## ch14 digital image compression

encoding, decoding

statistical, subjective, spatial, temporal redundancy

### lossless, entropy coding, source coding, differential coding

huffman coding - variable length conding, prefix property

### loss, interpolation, quantization, dct, wavelet transform

jpeg(joint photographic experts group)

mpeg(moving picture experts group) - gop(group of pictures)

h.264
