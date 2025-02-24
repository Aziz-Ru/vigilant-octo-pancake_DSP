# Sampling

## Continuous Time Signals

CTS are those signals that are continuous in both time and amplitude.

## Discrete Time Signals

DTS are those that are continuous in amplitude but discrete in time meaning that they are signals with values at some specific instants of time.

## Sampling

The Process of converting real world continous signal into discrete time signal by taking samples of their amplitude at regular interval is known as sampling.

## Sampling Rate or Sampling Frequency

It refers to the number of samples or data points taken per unit of time from an analog signal to convert it into a digital format.

```
SamplingRate= 1/T=F
​
```

## Nyquist Rate

It is the minimum sampling rate required to accurately capture an analog signal in digital form without information loss. It is also known as Nyquist Frequency or Nyquist Limit.

1. fs = Sampling Rate or Nyquist Rate (Hz)

2. fmax = Maximum frequency component (Hz)

```
fs=2*fmax
```

- If fs<2\*fmax , then it is the case of undersampling.

- If fs=2\*fmax then it is perfect sampling

- If fs>2\*fmax then it the oversampling

### Undersampling

the sampling rate is less than the Nyquist rate, making it impossible to extract the original signal from the sampled signal. Because the spectra overlap, some frequency components of the original signal will acquire a new frequency; this process is known as frequency aliasing.

## Aliasing

It is a phenomenon that occurs when a high-frequency signal is represented at lower frequency. Means it occurs when the sampling rate is insufficient and fails to capture the signal properly.

When the signals are sampled at lower frequency than the nyquist frequency, high frequency components fold back (gets aliased) in the low frequency range. This may lead to distorted signal representation.

### Methods to Avoid Aliasing

- Sampling at Nyquist Rate

- Using Anti-Aliasing Filter (Low Pass Filter):
