---
layout: default
title: "Statistical Inference in Finance — Course Outline"
---

<h1 style="margin-bottom: 24px; color: var(--primary);">Statistical Inference in Finance</h1>
<p style="font-size: 1.1rem; color: var(--text-light); margin-bottom: 24px;">2023 Cohort · 64 Teaching Hours · Sept 28 – Oct 23 · Changchun</p>

<div class="card">
  <h2>Course Overview</h2>
  <p>This 4-week intensive course delivers a rigorous foundation in statistical inference with direct applications to financial data analysis, risk modeling, and quantitative finance. Students master probability theory, estimation methods, hypothesis testing, and regression analysis through hands-on work with real financial datasets. The course emphasizes practical implementation in Python/R alongside theoretical understanding — graduates leave capable of applying statistical methods to real financial decision-making.</p>
  <div class="course-grid">
    <div class="course-card">
      <h4>📊 Format</h4>
      <p>Onsite instruction · 20–24 teaching hours/week · 1 teaching hour = 45 min</p>
    </div>
    <div class="course-card">
      <h4>🛠️ Tools</h4>
      <p>Python (SciPy, Statsmodels, Pandas) · R · Jupyter Notebooks</p>
    </div>
    <div class="course-card">
      <h4>📝 Assessment</h4>
      <p>Weekly problem sets · Midterm exam · Final project with financial dataset</p>
    </div>
  </div>
</div>

<div class="card">
  <h2>4-Week Syllabus</h2>

  <h3 style="margin: 20px 0 12px; color: var(--primary);">Week 1 — Probability Foundations & Distributions</h3>
  <div class="course-grid">
    <div class="course-card">
      <h4>Topics</h4>
      <ul style="margin-left: 16px; font-size: 0.9rem;">
        <li>Axioms of probability, conditional probability, Bayes' theorem</li>
        <li>Random variables: discrete vs continuous</li>
        <li>Expectation, variance, moments, moment-generating functions</li>
        <li>Key distributions: Normal, Binomial, Poisson, Log-normal</li>
        <li>Joint distributions, covariance, correlation</li>
      </ul>
    </div>
    <div class="course-card">
      <h4>Financial Application</h4>
      <ul style="margin-left: 16px; font-size: 0.9rem;">
        <li>Modeling asset returns with distributions</li>
        <li>Fat tails and non-normality in financial data</li>
        <li>Historical vs implied distributions</li>
      </ul>
    </div>
    <div class="course-card">
      <h4>Lab</h4>
      <ul style="margin-left: 16px; font-size: 0.9rem;">
        <li>Fit distributions to S&P 500 returns</li>
        <li>Visualize and test normality assumptions</li>
        <li>Compare historical vs normal quantiles</li>
      </ul>
    </div>
  </div>

  <h3 style="margin: 20px 0 12px; color: var(--primary);">Week 2 — Estimation Theory</h3>
  <div class="course-grid">
    <div class="course-card">
      <h4>Topics</h4>
      <ul style="margin-left: 16px; font-size: 0.9rem;">
        <li>Sampling distributions and Central Limit Theorem</li>
        <li>Point estimation: method of moments, maximum likelihood</li>
        <li>Properties: unbiasedness, consistency, efficiency</li>
        <li>Interval estimation: confidence intervals</li>
        <li>Fisher information and Cramér-Rao bound</li>
      </ul>
    </div>
    <div class="course-card">
      <h4>Financial Application</h4>
      <ul style="margin-left: 16px; font-size: 0.9rem;">
        <li>Estimating expected returns and volatility</li>
        <li>Confidence intervals for portfolio parameters</li>
        <li>MLE for GARCH models</li>
      </ul>
    </div>
    <div class="course-card">
      <h4>Lab</h4>
      <ul style="margin-left: 16px; font-size: 0.9rem;">
        <li>MLE estimation for stock return parameters</li>
        <li>Bootstrap confidence intervals</li>
        <li>Simulation: sampling distribution of estimators</li>
      </ul>
    </div>
  </div>

  <h3 style="margin: 20px 0 12px; color: var(--primary);">Week 3 — Hypothesis Testing</h3>
  <div class="course-grid">
    <div class="course-card">
      <h4>Topics</h4>
      <ul style="margin-left: 16px; font-size: 0.9rem;">
        <li>Null/alternative hypotheses, test statistics, p-values</li>
        <li>Type I/II errors, power of tests</li>
        <li>t-tests, z-tests, F-tests, chi-squared tests</li>
        <li>Likelihood ratio tests</li>
        <li>Multiple testing and family-wise error</li>
      </ul>
    </div>
    <div class="course-card">
      <h4>Financial Application</h4>
      <ul style="margin-left: 16px; font-size: 0.9rem;">
        <li>Testing mean reversion in stock prices</li>
        <li>Comparing portfolio performance (paired tests)</li>
        <li>Event study methodology</li>
      </ul>
    </div>
    <div class="course-card">
      <h4>Lab</h4>
      <ul style="margin-left: 16px; font-size: 0.9rem;">
        <li>Event study: earnings announcements impact</li>
        <li>Backtesting trading strategies with hypothesis tests</li>
        <li>Multiple testing corrections on factor models</li>
      </ul>
    </div>
  </div>

  <h3 style="margin: 20px 0 12px; color: var(--primary);">Week 4 — Regression & Applications</h3>
  <div class="course-grid">
    <div class="course-card">
      <h4>Topics</h4>
      <ul style="margin-left: 16px; font-size: 0.9rem;">
        <li>Simple and multiple linear regression</li>
        <li>OLS estimation and assumptions</li>
        <li>Hypothesis testing in regression (t, F, R²)</li>
        <li>Multicollinearity, heteroskedasticity</li>
        <li>Introduction to time series: AR, MA, ARMA</li>
      </ul>
    </div>
    <div class="course-card">
      <h4>Financial Application</h4>
      <ul style="margin-left: 16px; font-size: 0.9rem;">
        <li>CAPM and multi-factor models (Fama-French)</li>
        <li>Predicting returns with regression</li>
        <li>Volatility forecasting</li>
      </ul>
    </div>
    <div class="course-card">
      <h4>Lab & Final Project</h4>
      <ul style="margin-left: 16px; font-size: 0.9rem;">
        <li>Estimate Fama-French 3-factor model on Chinese stock data</li>
        <li>Final project: independent analysis of financial dataset</li>
        <li>Present findings with statistical justification</li>
      </ul>
    </div>
  </div>
</div>

<div class="card">
  <h2>Assessment Breakdown</h2>
  <div style="display: flex; gap: 16px; flex-wrap: wrap; margin-top: 12px;">
    <div style="flex: 1; min-width: 120px; background: #e3f2fd; padding: 16px; border-radius: 8px; text-align: center;">
      <strong style="font-size: 1.2rem; color: var(--primary);">30%</strong><br><span style="font-size: 0.85rem;">Weekly Problem Sets</span>
    </div>
    <div style="flex: 1; min-width: 120px; background: #e8f5e9; padding: 16px; border-radius: 8px; text-align: center;">
      <strong style="font-size: 1.2rem; color: #2e7d32;">20%</strong><br><span style="font-size: 0.85rem;">Midterm Exam</span>
    </div>
    <div style="flex: 1; min-width: 120px; background: #fff3e0; padding: 16px; border-radius: 8px; text-align: center;">
      <strong style="font-size: 1.2rem; color: #e65100;">40%</strong><br><span style="font-size: 0.85rem;">Final Project</span>
    </div>
    <div style="flex: 1; min-width: 120px; background: #f3e5f5; padding: 16px; border-radius: 8px; text-align: center;">
      <strong style="font-size: 1.2rem; color: #7b1fa2;">10%</strong><br><span style="font-size: 0.85rem;">Participation</span>
    </div>
  </div>
</div>

<div class="card">
  <h2>Materials Provided by Instructor</h2>
  <ul style="margin-left: 20px;">
    <li>Full PowerPoint lecture slides for all 64 hours</li>
    <li>Jupyter Notebook-based lab exercises with real financial data</li>
    <li>Weekly problem sets with solutions</li>
    <li>Midterm and final exam materials</li>
    <li>Recommended textbooks and supplementary readings</li>
  </ul>
</div>
