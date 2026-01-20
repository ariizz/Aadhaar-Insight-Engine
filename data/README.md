# 📊 Data Sources for Aadhaar Hackathon

The datasets used in this project are over 1GB each and are excluded from this repository to save space. To run the analysis, please download and extract the datasets into this `data/` folder.

## 📥 Download Links

1. **Aadhaar Enrolment Data**  
   [Download ZIP](https://www.data.gov.in/files/ogdpv2dms/s3fs-public/uidai/api_data_aadhar_enrolment.zip?X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=3656IQ2EG34EPEWQSBE9%2F20260120%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20260120T150110Z&X-Amz-SignedHeaders=host&X-Amz-Expires=1800&X-Amz-Signature=e9496c9156c3614f106211b4453b3b9b4a4681af6bfa8e5d0f638acefe5d431d)

2. **Aadhaar Demographic Data**  
   [Download ZIP](https://www.data.gov.in/files/ogdpv2dms/s3fs-public/uidai/api_data_aadhar_demographic.zip?X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=3656IQ2EG34EPEWQSBE9%2F20260120%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20260120T150110Z&X-Amz-SignedHeaders=host&X-Amz-Expires=1800&X-Amz-Signature=cc0904e4545c077cfd13f9b0ac72c123923cb2ccb0461b098b844ba7d5f74c26)

3. **Aadhaar Biometric Data**  
   [Download ZIP](https://www.data.gov.in/files/ogdpv2dms/s3fs-public/uidai/api_data_aadhar_biometric.zip?X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=3656IQ2EG34EPEWQSBE9%2F20260120%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20260120T150110Z&X-Amz-SignedHeaders=host&X-Amz-Expires=1800&X-Amz-Signature=42a25ea61186affdc3a174331ffbff5dc1298753fd5b329c66fea0ec70fe49b8)

## 📂 Setup Instructions

1. Download all three ZIP files.
2. Extract them directly into this `data/` folder.
3. Ensure the folder names are exactly:
   - `api_data_aadhar_enrolment/`
   - `api_data_aadhar_demographic/`
   - `api_data_aadhar_biometric/`

The analysis script in `notebooks/data_hack.py` will automatically look for these folders here.
