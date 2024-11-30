# Sensitivity and Dynamic Range
reference 《RF Microelectronics》Sec. 2.4. Sensitivity and Dynamic Range page 59

## 2.4 .1 Sensitivity
$$
NF=\frac{SNR_{in}}{SNR_{out}}=\frac{P_{sig,in}/P_{n,in}}{SNR_{out}}
$$
$$
P_{sig,in}=NF*P_{n,in}*SNR_{out}
$$
Since the overall signal power is distributed across a certain bandwidth, B,
$$
P_{sig,in,tot}=NF*P_{n,in}*SNR_{out}*B
$$
Expressing the quantities in dB or dBm, we have
$$
P_{sig,in,tot|dBm}=NF_{|dB}+P_{n,in|dBm/Hz}+SNR_{out|dB}+10*log(B)
$$
$$
P_{sen|dBm}=NF_{|dB}+P_{n,in|dBm/Hz}+SNR_{out,min|dB}+10*log(B)
$$
If the receiver is matched to the antenna,
$$
V_{n,in}=V_{n,Rs}*\frac{R_{in}}{R_{in}+R_{s}}
$$
$$
V_{n,in}^2=V_{n,Rs}^2*(\frac{R_{in}}{R_{in}+R_{s}})^2=4*k*T*R*1/4=k*T*R
$$ 
k=1.38*10^(-23)
T=273+25=298
$$
P_{n,in}=10*log(V_{n,in}^2/50)+30=10*log(k*T)+30=-173.8dBm/Hz
$$
Noise floor
$$
Noise Floor=NF_{|dB}+P_{n,in|dBm/Hz}+10*log(B)=−174dBm/Hz+NF_{|dB}+10*log(B)
$$

