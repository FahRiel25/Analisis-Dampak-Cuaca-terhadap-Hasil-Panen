# Open Data Source Analysis & Planning Project

## Project Information

**Project Name**: Analisis dampak cuaca terhadap produksi padi di Jawa Timur
**Created By**: Data Engineering Kelompok 1
**Date**: February 10, 2025
**Version**: 1.0

## 1. Executive Summary

### 1.1 Project Overview

- **Tujuan Project**: 
- **Scope Project**: 
- **Expected Outcomes**: 
- **Timeline**: 

### 1.2 Stakeholders

- **Project Owner**: 
- **Team Members**:
  - Data Engineer: Muhsyam Fahriel Septiansyah/244311021
  - Data Analyst: Jimli Dwi Assidiqi/
  - Project Manager: Satriyo Wicaksono Yunan Mubarok/
- **End Users**:
  - Masyarakat umum dan kelompok Tani

## 2. Data Source Analysis

### 2.1 Data Pemerintah (data.go.id)

#### Source Details

- **Dataset Name**: Produksi padi Menurut Kabupaten atau Kota 
- **URL/Access Point**: https://jatim.bps.go.id/id/statistics-table/2/NTc5IzI=/produksi-padi-menurut-kabupaten-kota--ton-.html
- **Data Owner**: Badan Pusat Statistika Jawa Timur
- **Update Frequency**: Monthly

#### Data Analysis

- **Format Data**: CSV
- **Volume Data**: 
- **Time Coverage**: Januari 2018 - Desember 2024
- **Data Quality**:
  - Completeness: 
  - Accuracy: High (verified by BPS)
  - Consistency: Good (format standar)
  - Timeliness: 
    

### 2.3 Public APIs

#### Source Details
- **API Name**: Open Meteo
- **Endpoint URL**: https://open-meteo.com/en/docs/historical-weather-api?latitude=-7.0265&longitude=112.7425&start_date=2018-01-01&end_date=2025-12-31&timezone=auto&hourly=&bounding_box=-90,-180,90,180&daily=temperature_2m_mean,precipitation_sum#hourly_weather_variables
- **Provider**: Open Meteo

#### API Analysis
- **Response Format**: CSV
- **Documentation Quality**: Comprehensive
- **Cost**: Free tier sufficient for project needs
