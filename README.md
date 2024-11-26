# Marcov-Chain-Monte-Carlo-MCMC
# Estimating Cosmological Parameters from Supernova Ia Data

This repository provides tools to estimate cosmological parameters using Supernova Ia data. The estimation is performed using Markov Chain Monte Carlo (MCMC) and Hamiltonian Monte Carlo (HMC) algorithms, which allow for efficient sampling from the posterior distributions of the parameters of interest. The repository also includes implementations of cosmological statistical models necessary for this analysis.

## Table of Contents

- [Introduction](#introduction)
- [Algorithms](#algorithms)
  - [Markov Chain Monte Carlo (MCMC)](#markov-chain-monte-carlo-mcmc)
  - [Hamiltonian Monte Carlo (HMC)](#hamiltonian-monte-carlo-hmc)
- [Cosmological Models](#cosmological-models)

## Introduction

Estimating cosmological parameters is crucial for understanding the fundamental properties and evolution of the universe. Supernova Ia data provides a reliable standard candle for measuring astronomical distances, which in turn helps constrain these parameters. This project utilizes advanced MCMC and HMC techniques to perform Bayesian inference on the cosmological parameters, leveraging the power of these algorithms to efficiently explore high-dimensional parameter spaces.

## Algorithms

## Markov Chain Monte Carlo (MCMC)

MCMC is a method for sampling from a probability distribution based on constructing a Markov chain that has the desired distribution as its equilibrium distribution.

## Hamiltonian Monte Carlo (HMC)

HMC is a method that augments the state space with auxiliary momentum variables and uses Hamiltonian dynamics to propose new states. This approach can improve the efficiency of the sampling process. We utilize the pymc3 library for implementing HMC.

## Cosmological Models

The repository includes several cosmological models that describe the universe's expansion. Users can select models such as the Lambda Cold Dark Matter (ΛCDM) model or more complex models involving additional parameters like dark energy equation of state.
