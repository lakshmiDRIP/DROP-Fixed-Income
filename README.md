#DRIP Fixed Income

**v2.63**  *1 February 2017*

DRIP Fixed Income is a collection of Java libraries for Instrument/Trading Conventions, Treasury Futures/Options, Funding/Forward/Overnight Curves, Multi-Curve Construction/Valuation, Collateral Valuation and XVA Metric Generation, Calibration and Hedge Attributions, Statistical Curve Construction, Bond RV Metrics, Stochastic Evolution and Option Pricing, Interest Rate Dynamics and Option Pricing, LMM Extensions/Calibrations/Greeks, Algorithmic Differentiation, and Asset Backed Models and Analytics.

DRIP Fixed Income is composed of the following main libraries:
 * Instrument/Trading Conventions Library
 * Treasury Futures/Options Library
 * Funding/Forward/Overnight Curve Library
 * Multi-Curve Construction/Valuation Library
 * Collateral and XVA Metrics Library
 * Position Horizon Analyzer Library
 * Statistical Curve Construction Library
 * Bond RV Metrics Library
 * Stochastic Evolution and Option Pricing Library
 * Interest Dynamics and Option Pricing Library
 * LMM Extensions, Calibration, and Greeks Library
 * Algorithmic Differentiation Library
 * Asset Backed Model Library

For Installation, Documentation and Samples, and the associated supporting Numerical Libraries please check out [DRIP] (https://github.com/lakshmiDRIP/DRIP).


##Features

###Instrument/Trading Conventions Library

####Associations and Exchanges
 * Associations
 * Exchanges

####Date Conventions
 * Day Count Conventions
 * Business Day Conventions

####Overnight and IBOR-like Indexes
 * IBOR Indexes - Introduction
 * Main IBOR Indices
 * Other IBOR Indices
 * Overnight Index Definitions
 * Overnight Index Committees and Meeting Dates

####Over the Counter Instruments
 * Forward Rate Agreement
 * Interest Rate Swaps
 * Vanilla IRS
 * Interest Rate Swaps (Basis Swaps: IBORfor IBOR)
 * Cross Currency Swaps (IBOR for IBOR)
 * Constant Maturity Swaps
 * Swap Indexes
 * Overnight Indexed Swaps
 * Swap Option
 * Forex and Forward Swaps

####Exchange Traded Instruments
 * Overnight Futures
 * Short-Term Interest Rate Futures (STIR Futures)
 * Currency Specific Futures
 * Interest Rate Futures Option - Premium
 * Interest Rate Futures Option - Margin
 * Bank Bill Futures - AUD Style
 * Deliverable Swap (IRS) Futures (PV Quoted)
 * Bond Futures (non AUD/NZD)
 * Country Specific Bond Futures - USD
 * Country Specific Bond Futures - Germany
 * Country Specific Bond Futures - Spain
 * Country Specific Bond Futures - UK
 * Country Specific Bond Futures - Japan
 * Options on Bond Futures (non AUD/NZD) - Premium
 * Options on Bond Futures (non AUD/NZD) - Margin
 * AUD-NZD Bond Futures

###Treasury Futures/Options Library
####Treasury Futures Trading and Hedging
 * Contract Detail Specifications

####Identification of the CTD in the Basket
 * The Conversion Factor
 * Old vs. Active Treasury
 * Market Parameters Influencing the CTD Calculation
 * Impact of Yield Curve Changes

####Valuation of Treasury Futures Contract
 * Futures Contract and Mark-To-Market
 * Role of the Clearing Corporation
 * Delivery Options for the Underlying
 * Implied Basis for the Futures
 * Net Basis For Treasury Futures

###Funding/Forward/Overnight Curve Library

####Curve Builder Features
 * Discount Curves

####Curve Construction Methodology
 * Approach
 * State Span Design Components
 * Curve Calibration From Instruments/Quotes
 * Calibration Considerations

####Curve Construction Formulation
 * Segment Linear Discount Curve Calibration
 * Curve Jacobian

####Stream Based Calibration
 * Latent State Formulation Metric (LSFM)
 * Stream Inference Setup
 * Coupon Period Based Calibration Specification
 * Stream Based Calibration Specification
 * Calibration of Multi-Stream Components

####Spaning Splines
 * Setup and Formulation
 * Challenges with the Spanning Spline Approach

####Monotone Descreasing Splines
 * Exponential Rational Basis Spline
 * Exponential Mixture Basis Set

####Hagan-West (2006) Smoothness Preserving Spanning Spline
 * Monotone/Convexity Preserving Estimator
 * Positivity Preserving
 * Ameliorating Estimator
 * Harmonic Spline Extension to the Framework above
 * Minimal Quadratic Estimator

####Extrapolation in Curve Construction

####Multi-Pass Curve Construction
 * Bear-Sterns Multi-Pass Curve Building Techniques

####Transition Spline (Or Stitching Spline)
 * Stretch Modeling using Transition Splines
 * Stretch Partition/Isolation in Transition Splines
 * Knot Insertion vs. Transition Splines
 * Overlapping Stretches

####Penalizing Exact/Closeness of Fit and Curvature Penalty

####Index/Tenor Basis Swaps
 * Component Layout and Motivation
 * Formulation

####Multi-Stretch Merged Curve Construction
 * Merge Stretch Calibration

####Latent State Manifest Measure Sensitivity
 * Float-Float Manifest Measure Sensitivities
 * Multi-reset Floating Period

####OIS Valuation and Curve Construction
 * Base Framework and Environment Setup
 * OIS Valuation Extensions and Approximations
 * OIS-FX Basis Swap Valuation and Approximations
 * Arithmetic Accrual Convexity Correction
 * Composed Period Latent State Loadings

####Spline Based Credit Curve Calibration

###Multi-Curve Construction/Valuation Library

####Correlated Multi-Curve Build-out
 * Standard FRA Setup
 * Standard FRA Options
 * No arbitrage and Counter-party Risk Based Standard FRA Formulation
 * Market FRA Setup
 * Futures
 * Multi-Curve Swap Valuation

####Cross Currency Basis Swap
 * Product Details and Valuation
 * Building the CCS Discount Curve
 * Custom CCBS Based Curve Construction SKU
 * Mark-To-Market Cross-Currency Swap Valuation
 * Mark-To-Market Cross-Currency Swap - Valuation Formulation
 * Absolute/Relative MTM Application
 * Per-Trade Risk Isolation Components

###Collateral and XVA Metrics Library

####Collateral Agreements and Derivatives Valuation
 * Two Collateralized Assets
 * Setup pf the Collateral Curve Dynamics
 * Collateralized Black-Scholes Formulation
 * Collateralization and Funding Derivative Valuation
 * Collateral PDE Formulation
 * Formward Contract Valuation
 * European Style Options
 * Cross-Currency Model
 * Collateral Choice Model

####CVA and Funding Adjustments PDE
 * Counterparty Risk and Funding Costs
 * Notation, Symbology, and Key PDE's
 * Model Setup and the Derivation of the Bilateral Risky PDE
 * Using VHat (T, S) and Mark-To-Market at Default
 * Using V (T, S) and Mark-To-Market at Default
 * Funding and Default Payoff Examples
 * Counter-party Funding and PDE Extensions
 * Balance Sheet and Funding Cost Management
 * Unified Framework for Bilateral Counterpart Risk and Funding Adjustments
 * Simple Model for the Impact of Derivative Asset on Balance Sheet and Funding
 * Balance Sheet Management to Mitigate Funding Costs
 * Funding Strategies and Costs Impact
 * Generalized Semi-replication and Pricing PDE
 * Semi-replication
 * Examples of Different Bond Portfolios
 * The Perfect Replication - FCA Vanishes
 * Semi-replication with no Shortfall at own Default
 * Set-offs
 * Semi-replication with a Single Bond
 * Burgard and Kjaer (2013) Case Study

####Accounting for OTC Derivatives: Funding Adjustments and Re-hypothecation Option
 * Status of Currenct FCA/FBA Accounting
 * Comaprison between FCA/FBA and FVA/FDA
 * OTC vs. Repo Markets
 * Modus Operandi of Funding Desks
 * MTM and the Asset Liability Symmetry
 * Rigorous Framework for Funding Costs
 * Funding Set VM RHO Computation
 * Shortcomings of Traditional CVA Systems
 * Addressing the Shortcomings of FCA/FBA Accounting
 * Valuation Adjustment Estimation Framework Setup
 * OTC Bookds Funding Set Decomposition
 * Inconsistent Booking under the FCA/FBA
 * Improvements Offered by the FVA/FDA Accounting
 * CET1 Deductions
 * "Going Concern" or Defaulable Banks
 * Cash Flow Streams Categorization
 * Accounting Rules
 * Contra-Asset and Contra-Liability Accounting for Credit Risk
 * Contra-Asset and Contra-Liability Accounting for Funding
 * Accounting Cash Flow Setup Framework
 * Cash Flows related to VM Funding
 * Cash Flows at Counter-party Default
 * Cash Flows at Bank Default
 * CVA and DVA
 * FVA and FDA
 * FCA and FBA
 * CA and CL Adjustments
 * Own Credit Sensitivities
 * Triggers and Close-out Adjustments
 * Collateral Triggers and Close-outs
 * Incorporating ISDA 1992 Close-outs
 * VM Re-hypothecability across Funding Sets
 * Trade and Portfolio FTP Estimation
 * FTP for FCA/FBA Accounting
 * FTP for FVA/FDA Accounting
 * Exit Prices and Fair Valuation
 * FVA/FDA Accounting
 * FCA/FBA Accounting
 * Liquidity Spreads, Asset Liability Symmetry, and Alternative Allocations for Excess Collateral
 * Working Capital Management and Operations
 * Equity Gain and Debt Gain
 * Liquidity Based Analysis and Treatment
 * Problems with Gain Accounting
 * Albanese and Andersen (2014) Case Study
 * Case Study Setting and Purpose
 * Scenario Estimation of the XVA Metrics
 * Product and Scenario Threshold Type Scenarios
 * XVA Error Metrics and Incrementals
 * Estimation ofthe FCA/FBA - FVA/FDA Mismatch
 * Traditional Challenges with Derivative Accounting
 * Problems with FCA/FBA Accounting
 * FVA/FDA vs. FCA/FBA Enhancement
 * Trading Staff Point of View
 * Challenges with the XVA Metric Estimation
 * Shortfalls of the FVA/FDA Scheme
 * Alternate Specialized Value Metrics

###Position Horizon Analyzer Library

####Convexity Corrections Associated with Margining

####Hedging Considerations

####Product Curve Effect Attribution
 * Market Value Change Explain Components
 * Coupon Accrual Intrinsic
 * Market Parameters Intrinsic
 * Market Parameters Extrinsic
 * Market Value Change Effects Formulation

###Statistical Curve Construction Library

####Inference Based Curve Construction
 * Curve Smoothing in Finance
 * Bayesian Curve Calibration
 * Sequential Curve Estimation

###Bond RV Metrics Library
 * The Bond RV Measure Set
 * Asset Swap Spread
 * Bond Basis
 * Convexity
 * Credit Basis
 * Discount Margin
 * Duration
 * DV01
 * G Spread
 * I Spread
 * Macaulay Duration
 * Modified Duration
 * Option Adjusted Spread
 * Par Asset Swap Spread
 * Par Spread
 * Par Equivalent CDS Spread (PECS)
 * Price
 * Spread Over Treasury Benchmark
 * Yield
 * Yield Basis
 * Yield Spread
 * Yield01
 * Zero Discount Margin (ZDM)
 * Z Spread
 * Relative Value Cross-Metric Grid
 * Basic Measures

###Stochastic Evolution and Option Pricing Library

####Stochastic Calculus
 * Single-Factor Stochastic Calculus
 * Multi-Factor Stochastic Calculus
 * Risk Neutral Pricing Framework

####Black Scholes Methodology
 * The Replication Technique
 * Capital Asset Pricing Model
 * Multi-numeraire Formulation
 * First Order Log-normal Black Scholes Greeks
 * Second Order Log-normal Black Scholes Greeks
 * Third Order Log-normal Black Scholes Greeks
 * Time-Dependent Black Scholes
 * Local Volatility Models
 * Black Normal Model Specification and Dynamics
 * Options on Forward
 * The Black76 Model

####Stochastic Volatility Models: The Heston Model
 * Model Specification and Dynamics
 * Price Estimation Through Characteristic Functions
 * Fourier Inversion in Characteristic Function

####Dynamical Latent State Calibration
 * Fokker-Planck Equations
 * Volatility Observations vs. Calibrations

###Interest Rate Dynamics and Option Pricing Library

####HJM Model
 * Formulation
 * Hull-White from HJM
 * G2++ - A 2-Factor HJM Model
 * HJM to LMM
 * HJM PCA

####Hull-White Model
 * Short-Rate Formulation
 * Hull-White Trinomial Tree
 * Construction of the Symmetric Trinomial Tree
 * Displacing the Nodes of the Trinomial Tree

####Market Model fo Interest Rate Dynamics
 * Nomenclature and Notation
 * The BGM Model
 * LIBOR Rate Dynamics
 * Relation to the HJM Dynamics
 * Existence, Uniqueness, and Regularity of the LIBOR Dynamics Solution
 * Upper/Lower Bounds for the LIBOR Rate
 * Invariant Measure for the LIBOR Rate
 * BGM Cap/Floor Pricing
 * Payer Swap Option Pricing
 * Payer Swap Option Pricing Simplification
 * Mismatched Periods Cap/Swaption Pricing
 * Approximate vs. Full Simulation Comparisons
 * Typical Model Calibration Results

####The SABR Model
 * Parameter Estimation

###LMM Extensions, Calibration, and Greeks Library

####LMM Calibration and Greeks Overview
 * Robust LMM Calibration Approaches Overview
 * Cross-Currency LIBOR Market Model
 * LMM Based Greeks Calculation Approaches
 * Major Extensions to LMM
 * Hedging the Derivatives Cash Flow
 * LMM Skew and its Calibration
 * LMM Smile and its Calibration
 * Cross-Currency Extensions to LMM
 * LMM Monte-Carlo Methods and Greeks
 * Numerical Methods for LMM Calibration

###Algorithmic Differentiation Library
 * Algorithmic Differentiation in Finance
 * Program Sequence Construction Modes
 * Canonicalization - Program Statements Simplification by Decomposition
 * Challenges of Automating the Differentiation
 * Wengert Representation and Optimal Program Structure Synthesis
 * Optimization using Pre-accumulation and Check-Pointing
 * Algorithmic Differentiation Financial Application Space Customization
 * Sensitivity Generation During Curve Construction
 * Curve Jacobian
 * Stochastic Entity Evolution - Sensitivity Formulation
 * Sensitivities to Stochastic State Variates and Dynamical Parameters
 * State Variate Evolution Constrained by Splines
 * Formulation of the Evolution of the Stochastic Variate Self-Jacbian
 * Correlated Stochastic Variates Evolution
 * LMM Forward Rate Evolution
 * Formulation of the Pay-off Function Stochastic Evolution
 * Path Greeks
 * Pay-off Sensitivity to the Correlation Matrix
 * Algorithmic Differentiation in Pay-off Sensitivities Calculation
 * Bermudan Swap Option Sensitivities Formulation
 * Bermudan Swap Option Sensitivites Greek Estimation
 * LSM Methodology
 * NTD Basket Sensitivities Product Formulation
 * Basket Options

###Asset Backed Model Library
 * Overview of the Credit Model Methodology
 * Scope of the Model
 * Data Model Construction Rules
 * Loan Data Quality Rules
 * Lending Club Loan Level Data
 * Loan Credit Model Implementation
 * Credit Model Selection Methodology
 * Regressor Contribution Weights
 * Empirical Analysis of Seasoning Effects
 * Analysis of the Vintage/Cohort Effects
 * Analysis of the Empirical Seasonality Effects
 * CPR and CDR Curve Estimation
 * Credit Model Enhancements


##Contact

lakshmi@synergicdesign.com
