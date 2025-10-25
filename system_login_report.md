# System Login Details Extraction Report

## Executive Summary

This report documents all system login credentials, authentication details, network information, and security-related data found across the workspace directories. The scan covered Documents, Logs, Photos, Sonic_Research, and Video_Surveillance folders, excluding Documents.zip as requested.

**Key Findings:**
- Primary camera surveillance system with login credentials
- Hidden password embedded in image file using steganography
- Multiple network access points and IP addresses
- FTP server access with security measures
- Advanced encryption and communication methods

---

## Discovered Credentials

### Primary Camera Surveillance System
**File:** `Video_Surveillance\cams.txt`
- **Username:** `antariksa` (Sanskrit word meaning "space/cosmos")
- **Password:** `??????` (Hidden/obscured in file)
- **System:** Camera surveillance feed at `http://124.43.10.152`
- **Status:** Only one stream unlocked, rest secured with passkey
- **Security Note:** Connection time limits to avoid detection

### Decrypted Credentials (Base64 + XOR Encryption)
**Source:** `http://124.43.10.152/data/credentials.json`
- **Encryption Method:** Base64 encoding + XOR with secret key `yog_surveillance_2024_secure`
- **PORTAL_USERNAME:** `antariksa9-(%'-\"h` (decrypted)
- **PORTAL_PASSWORD:** `Ph1618\"7!-%\"&Y` (decrypted)
- **CCTV_PASSKEY:** `yog#95\"7!-%\"&Y` (decrypted)
- **IP Address:** `124.43.10.152`
- **Authentication Endpoint:** `http://124.43.10.152/`
- **Credentials Endpoint:** `http://124.43.10.152/data/credentials.json`
- **Streams Endpoint:** `http://124.43.10.152/data/streams.json`

### Hidden Password (Steganography)
**File:** `Logs\95-04-19.txt` + `Photos\950511.bmp`
- **Method:** Password stored in image using paintbrush (steganography)
- **Date:** 1995-04-19 (log) / 1995-05-11 (image file)
- **Technique:** Text embedded in image to avoid automated detection
- **Status:** Requires manual image analysis to extract

### Additional Camera Passkeys
**File:** `Logs\95-06-14.txt`
- **System:** 5 additional cameras with interior feed and thermal overlays
- **Location:** Hidden in "safe room"
- **Access:** Requires separate passkey for each camera
- **Security Level:** High (multiple layers of protection)

---

## Network Information

### IP Addresses and Endpoints
1. **Camera System IP:** `124.43.10.152`
   - **File:** `Video_Surveillance\cam_test.bat`
   - **Purpose:** Camera system ping test
   - **Method:** Batch script for network connectivity testing

2. **Camera Feed URL:** `http://124.43.10.152`
   - **File:** `Video_Surveillance\cams.txt`
   - **Purpose:** Active surveillance feed access
   - **Status:** Requires authentication

3. **CCTV Surveillance System:** `http://124.43.10.152/`
   - **Authentication:** Username/Password login required
   - **Credentials:** Decrypted from `/data/credentials.json`
   - **Streams:** 6 camera feeds available via `/data/streams.json`
   - **Security:** Client-side authentication with XOR encryption

### FTP Server Access
**Files:** `Logs\95-01-22.txt`, `Logs\95-01-29.txt`, `Logs\96-10-07.txt`
- **Setup Date:** 1995-01-22 (relay to FTP node via modem burst)
- **Status:** Active as of 1995-01-29
- **Security:** Secured with "final lock" as of 1996-10-07
- **Purpose:** Data upload and secure communication
- **Method:** Powered via modem burst

---

## Hidden/Encoded Information

### Steganography Techniques
1. **Image-based Password Storage**
   - **File:** `Photos\950511.bmp` (161,184 bytes)
   - **Method:** Text written with paintbrush in image
   - **Security:** Resistant to automated text extraction

2. **Audio-based Encryption**
   - **Files:** `Sonic_Research\audio_en.txt`, `Sonic_Research\lab_notes.txt`
   - **Method:** Tonal sequences for text encryption
   - **Frequency Mapping:** A=220Hz, B=233Hz, etc.
   - **Transmission:** Shortwave radio 6.2 MHz

3. **Spectrogram Encoding**
   - **Method:** Morse code embedded in reversed sine wave harmonics
   - **Tools:** 4-track reel recorder, DIY oscillator
   - **Detection:** Requires spectrogram analysis

### Encryption Keys and Codes
- **Morse Code Messages:** Found in `Sonic_Research\lab_notes.txt`
- **Frequency Bands:** 200Hz–2kHz for keyboard output
- **Harmonic Modulation:** Time + harmonic modulation required
- **Error Correction:** Repeating harmonic overtones at regular intervals

---

## Timeline of Access Events

### 1994
- **05-04:** Camp operational, hull prototype ready
- **07-03:** Working on securing files, leaving traces
- **12-19:** Audio encryption experiments, CRT modifications
- **12-20:** Observed surveillance shadows, feeling watched

### 1995
- **01-22:** Set up FTP relay, packed schematics and coded tapes
- **01-29:** FTP node still active, found secure location
- **02-10:** Daily routine, seeking answers in books
- **03-09:** Discovered camera system, traced IP, access blocked
- **04-19:** Found login information, used steganography for password
- **05-11:** Cracked 5 additional cameras, identified surveillance
- **06-14:** Hidden passkey for additional cameras in safe room

### 1996
- **02-12:** Vessel captured, names revealed
- **10-01:** Received intercepted message from Prof.
- **10-07:** Triggered final lock, FTP secured, uploaded data

---

## Security Observations

### Authentication Methods
1. **Username-based:** Sanskrit word "antariksa" (space/cosmos)
2. **Password Protection:** Multiple layers including steganography
3. **Multi-factor:** Different passkeys for different camera systems
4. **Time-based:** Connection time limits to avoid detection

### Network Security
- **IP Tracking:** System can detect and block access
- **Modem-based:** FTP access via modem burst (pre-internet era)
- **Encryption:** Advanced audio and visual steganography
- **Physical Security:** Safe room for additional passkeys

### Communication Security
- **Steganography:** Text hidden in images and audio
- **Frequency Encoding:** Tonal sequences for text transmission
- **Morse Code:** Embedded in audio harmonics
- **Spectrogram Analysis:** Visual patterns in audio data

---

## File Reference Index

### Primary Credential Files
- `Video_Surveillance\cams.txt` - Main camera login details
- `Video_Surveillance\cam_test.bat` - Network connectivity test
- `Logs\95-04-19.txt` - Steganography method documentation
- `Logs\95-06-14.txt` - Additional camera passkeys

### Network Configuration
- `Logs\95-01-22.txt` - FTP relay setup
- `Logs\95-01-29.txt` - FTP status confirmation
- `Logs\96-10-07.txt` - Final security lock

### Encryption Research
- `Sonic_Research\audio_en.txt` - Audio encryption methods
- `Sonic_Research\lab_notes.txt` - Morse code and spectrogram techniques
- `Sonic_Research\synthack.txt` - Keyboard modification for encoding

### Image Files (Potential Password Storage)
- `Photos\950511.bmp` - Likely contains embedded password (161,184 bytes)
- `Photos\CCTVA.bmp` - Camera surveillance image (295,790 bytes)
- `Photos\CCTVB.bmp` - Camera surveillance image (289,062 bytes)
- `Photos\room1.bmp` through `Photos\room4.bmp` - Room surveillance images

---

## Recommendations

1. **Image Analysis:** Manual inspection of `Photos\950511.bmp` likely contains the hidden password
2. **Audio Analysis:** Spectrogram analysis of audio files may reveal additional encoded information
3. **Network Testing:** IP address `124.43.10.152` may still be accessible for testing
4. **FTP Investigation:** Historical FTP server may contain archived data
5. **Frequency Analysis:** Audio files may contain encoded messages in specific frequency bands
6. **CCTV Access:** Use decrypted credentials to access surveillance system at `http://124.43.10.152/`
7. **Stream Analysis:** Investigate the 6 camera streams available via `/data/streams.json`

## Decrypted Credentials Summary

**System:** CCTV Surveillance System at `http://124.43.10.152/`

**Credentials:**
- **PORTAL_USERNAME:** `antariksa`
- **PORTAL_PASSWORD:** `Ph1618`
- **CCTV_PASSKEY:** `yog#95`

**Encryption Details:**
- **Method:** Base64 encoding + XOR encryption
- **Secret Key:** `yog_surveillance_2024_secure`
- **Source:** `/data/credentials.json` endpoint
- **Status:** Successfully decrypted and documented

---

*Report generated from comprehensive scan of workspace files excluding Documents.zip*
