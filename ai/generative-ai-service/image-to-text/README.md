
# Image-to-Text with Oracle OCI Gen AI

This application is built using **Streamlit** and **Oracle OCI Generative AI**, allowing users to upload an image, input a prompt, and receive a text-based response generated by the AI model. It leverages Oracle's Gen AI Inference API for processing multimodal data (text and image).

Reviewed: 19.11.2024

<img src="./image1.png">
</img>

---

## Features

- Upload an image file (`.png`, `.jpg`, `.jpeg`).
- Provide a natural language prompt describing your query about the image.
- Get a detailed response generated by Oracle's Generative AI model.
- Easy-to-use interface built with Streamlit.

---

## Prerequisites

1. **Oracle OCI Configuration**
   - Set up your Oracle Cloud Infrastructure (OCI) account.
   - Obtain the following:
     - **Compartment OCID**
     - **Generative AI Service Endpoint**
     - **Model ID** (e.g., `meta.llama-3.2-90b-vision-instruct`).
   - Configure your `~/.oci/config` file with your profile details.

2. **Python Environment**
   - Install Python 3.8 or later.
   - Install required dependencies (see below).

---

## Installation

1. Clone the repository:
  

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Configure OCI:
   Ensure your `~/.oci/config` file is set up with the correct credentials and profile.

---

## Usage

1. Run the application:
   ```bash
   streamlit run app.py
   ```

2. Open the web application in your browser at `http://localhost:8501`.

3. Upload an image and provide a prompt in the text input field. Click **Generate Response** to receive the AI-generated output.

---

## File Structure

```plaintext
.
├── app.py                  # Main application file
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## Dependencies

List of dependencies (found in `requirements.txt`):
- **Streamlit**: For creating the web UI.
- **oci**: Oracle Cloud Infrastructure SDK.
- **base64**: For encoding images.

Install them using:
```bash
pip install -r requirements.txt
```

---

## Notes

- Ensure your OCI credentials and Compartment OCID are correct in the script.
- Check the image format and size for compatibility.
- Use the appropriate Generative AI service endpoint for your region.

---

## Troubleshooting

- **Error: `oci.exceptions.ServiceError`**
  - Check if your compartment OCID and API keys are configured correctly.
  
- **Streamlit does not load:**
  - Verify that Streamlit is installed and the application is running on the correct port.



---

## Acknowledgments

- [Oracle Cloud Infrastructure (OCI)](https://www.oracle.com/cloud/)
- [Streamlit Documentation](https://docs.streamlit.io/)
  
For questions or feedback, please contact [anshuman.p.panda@oracle.com].



## Contributing
<!-- If your project has specific contribution requirements, update the
    CONTRIBUTING.md file to ensure those requirements are clearly explained. -->

This project welcomes contributions from the community. Before submitting a pull
request, please [review our contribution guide](./CONTRIBUTING.md).

## Security

Please consult the [security guide](./SECURITY.md) for our responsible security
vulnerability disclosure process.

## License
Copyright (c) 2024 Oracle and/or its affiliates.

Licensed under the Universal Permissive License (UPL), Version 1.0.

See [LICENSE](LICENSE.txt) for more details.

ORACLE AND ITS AFFILIATES DO NOT PROVIDE ANY WARRANTY WHATSOEVER, EXPRESS OR IMPLIED, FOR ANY SOFTWARE, MATERIAL OR CONTENT OF ANY KIND CONTAINED OR PRODUCED WITHIN THIS REPOSITORY, AND IN PARTICULAR SPECIFICALLY DISCLAIM ANY AND ALL IMPLIED WARRANTIES OF TITLE, NON-INFRINGEMENT, MERCHANTABILITY, AND FITNESS FOR A PARTICULAR PURPOSE.  FURTHERMORE, ORACLE AND ITS AFFILIATES DO NOT REPRESENT THAT ANY CUSTOMARY SECURITY REVIEW HAS BEEN PERFORMED WITH RESPECT TO ANY SOFTWARE, MATERIAL OR CONTENT CONTAINED OR PRODUCED WITHIN THIS REPOSITORY. IN ADDITION, AND WITHOUT LIMITING THE FOREGOING, THIRD PARTIES MAY HAVE POSTED SOFTWARE, MATERIAL OR CONTENT TO THIS REPOSITORY WITHOUT ANY REVIEW. USE AT YOUR OWN RISK. 