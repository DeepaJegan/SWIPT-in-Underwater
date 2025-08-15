# Performance Enhancement of SWIPT by Utilizing the Distance Dependent Bandwidth of Underwater Channel for Cooperative NOMA based UASNs

**Journal:** IEEE Latin American Transactions  
**ID No:** 9685  

**Authors:**  
- Deepa R  
- V. P. Harigovindan (Corresponding Author)  
- Veerapu Goutham  

**Affiliations:**  
- Department of Electronics and Communication Engineering, National Institute of Technology Puducherry, Karaikal 609609, India (Deepa R; V. P. Harigovindan)  
- Department of Communication Engineering, School of Electronics Engineering, Vellore Institute of Technology, Vellore, Tamil Nadu 632014, India (Veerapu Goutham)  

---

## 📄 Description

This repository contains the MATLAB implementation of the improved SWIPT (Simultaneous Wireless Information and Power Transfer) schemes proposed in the paper *Improved SWIPT Schemes for Underwater Acoustic Sensor Networks (UASNs)*.

Traditional PS-SWIPT and TS-SWIPT cooperative NOMA schemes do not fully utilize distance-dependent bandwidth in underwater environments.  

In this work, we propose two enhanced methods:

- **IPS-SWIPT-CNOMA**: Improved Power Splitting scheme  
- **ITS-SWIPT-CNOMA**: Improved Time Switching scheme  

These methods exploit additional bandwidth for enhanced energy harvesting, resulting in a **positive energy balance** to support energy-limited UASNs.

---

## 📂 Included Scripts

This repository contains all scripts required to reproduce the simulation and numerical results presented in the article.

| Script         | Related Figure(s) | Description |
|----------------|-------------------|-------------|
| `IPSSWIPT.mlx` | Fig. 4, Fig. 5, Fig. 6 | MATLAB Live Script implementing IPS-SWIPT-CNOMA scheme for underwater acoustic sensor networks. Simulates power splitting, time switching, and improved bandwidth utilization for enhanced energy harvesting. Produces all plots and numerical results from the paper. |
| `ITSSWIPT.mlx` | Fig. 4, Fig. 5, Fig. 6 | MATLAB Live Script implementing ITS-SWIPT-CNOMA scheme for underwater acoustic sensor networks. Simulates power splitting, time switching, and improved bandwidth utilization for enhanced energy harvesting. Produces all plots and numerical results from the paper. |

---

## 📂 Required Files

- `channel_data.mat` : Required for both `IPSSWIPT.mlx` and `ITSSWIPT.mlx`. Contains underwater channel characteristics and parameters used for simulation.  
- `system_params.mat` : Contains system configuration parameters, including transmission power, energy harvesting efficiency, and network topology.  
- All `.mlx` scripts are standalone once the required `.mat` data files are placed in the same directory.
