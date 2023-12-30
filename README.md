# StreamlinePlay
Direct Upload Edition
=====================================

Overview
--------

StreamlinePlay is an automated Python script designed to streamline the process of sharing gameplay videos. It simplifies the uploading of gaming content to YouTube by automating video detection, watermarking, uploading, and file management.

Features
--------

*   **Automated Video Detection**: Monitors a specified folder for new gameplay videos.
*   **Watermarking**: Adds a unique watermark to videos for consistent branding.
*   **YouTube Uploading**: Automatically uploads watermarked videos to YouTube.
*   **File Management**: Organizes videos by moving processed files to a designated folder.

Getting Started
---------------

### Prerequisites

*   Python 3.x
*   OBS (Open Broadcaster Software) for recording videos
*   Google/YouTube Data API credentials
*   Python Libraries: moviepy, google-auth, google-auth-oauthlib, google-auth-httplib2

### Installation

1\. Clone the repository:

    git clone https://github.com/mangrv/StreamlinePlay.git

2\. Install the required Python libraries using the following commands (for both Ubuntu and macOS):

    
    # Update pip
    python3 -m pip install --upgrade pip
    
    # Install moviepy
    pip3 install moviepy
    
    # Install Google API client libraries
    pip3 install google-auth google-auth-oauthlib google-auth-httplib2
    

### Usage

1\. Set up your OBS to save recordings to the monitored folder.

2\. Configure your YouTube API credentials in the script.

3\. Run the script:

    python streamlineplay.py

### Configuration

Edit the `config.py` file to set up your video folder paths, YouTube API credentials, and watermark settings.

Contributing
------------

Contributions to StreamlinePlay are welcome! Please read the `CONTRIBUTING.md` for details on our code of conduct and the process for submitting pull requests.

License
-------

This project is licensed under the [GNU General Public License version 3.0 (GPLv3)](https://www.gnu.org/licenses/gpl-3.0.html) - see the `LICENSE.md` file for details.

Acknowledgments
---------------

*   OBS Community
*   YouTube API Team
*   Moviepy Library Contributors

Contact
-------

For any inquiries, please open an issue or contact me at [info@mangrv.com](mailto:info@mangrv.com).