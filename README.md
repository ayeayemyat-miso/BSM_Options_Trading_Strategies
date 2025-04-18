# BSM_Options_Trading_Strategies

# Options Analysis & Trading Strategies (Derivative Related Tools) 
*Excel | VBA | Python | Google Collab*  

# 🗂️ Project Structure  
 *Single Master Excel File*: Contains all models (BlackScholes, trading strategies, sensitivity analysis).  
 *Google Colab Links*: Separate notebooks for Python/C++ verification and visualizations.  

# 🔗 Quick Access  
[📥 Download Master Excel File (MacroEnabled)]( https://drive.google.com/file/d/1fomUolMIsr4jPB4Cn2HLFErfo8K2eSBx/view?usp=drive_link).  
1. *Enable macros via `File > Options > Trust Center`.*
Otherwise
2. *Unblock File (Windows)*:  
   - Right-click the downloaded file > *Properties* > Check *Unblock* > Apply.  

# 📁 Topics & Colab Verification  
## 1. BlackScholes Model Implementation  
*Tools*:  
 *Excel/VBA*: European call/put pricing
*Python/C++*: Verification in Colab.  
*Features*:  
 Dynamic parameter inputs (S, K, T, σ, r, q).  
 Replication of Hull’s Figure 11.1a with custom parameters.  
 Scatter plots for time value vs. stock price.  
🔗 [Google Colab Verification]( https://colab.research.google.com/drive/1meP07-aZGU1FtxbuLEcE3Yq0Zdx_Du3Y?usp=sharing).  


## 2. Option Parabola & Sensitivity Analysis  
*Tools*:  
*Excel*: Data Tables for Sensitivity Analysis. 
*Features*:  
 Steepness factors: Volatility (σ) > Time (T) > Dividend (q).  
 Comparison of intrinsic vs. time value.  


## 3. Implied Volatility & Surface Modeling  
*Tools*:  
 *VBA*: Bisection method for Yahoo Finance data.  
*Features*:  
 Filtered by moneyness and run regression  and create Volatility Surface 

## 4. Option Trading Strategies  
*Tools*:  
 *Excel/VBA*: Butterfly, calendar spread, bull spread payoffs.  
*Features*:  
 Strategy analysis under varying volatility/maturity.  



# 📊 Key Visualizations  
1. BlackScholes Call Parabola  
2. Implied Volatility Surface (3D)  
3. Trading Strategies (Butterfly, Bull etc)   

# 🛠️ How to Use  
1. *Excel*:  
    Navigate via tabs (e.g., "Black_Scholes_Call_and_Put").  

# 📚 References  
Hull, J.C. *Options, Futures, and Other Derivatives* (Ch. 11, 238).  

# ⚠️ Compliance & Attribution  
 *Credits*: VBA logic adapted from [Vinegar Hill Labs] 
 *Licensing*: MIT License for original code.  
 *Data*: Yahoo Finance option chains (cleaned/public).  
