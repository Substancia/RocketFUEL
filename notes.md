# Project RocketFUEL (vehicle-perf-analyzer)

## Proposal

### Collection

1. Have an Android app designed to input and record different metrics (distance, re-fuel frequency and time and rate etc)
2. Make the app send the data to a hosted server (AWS?)
3. Have a backend server designed to receive and store data sent by Android app

### Analysis

(TBD)

## Infrastructure

1. Storage: RDS (for daily collection), S3 (for long-term storage)
2. Compute: Lambda (Proxy from API Gateway)
3. Deployment: AWS CDK (TS)

## Backend

1. Language: Go
2. Auth: JWT

## Frontend

1. Language: React Native
