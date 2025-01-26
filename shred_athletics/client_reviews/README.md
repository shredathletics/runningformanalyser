# Client Reviews Organization

## Folder Structure
```
client_reviews/
├── review_template.html
├── clients/
│   ├── [client_name]/
│   │   ├── 2024-03/
│   │   │   └── monthly_review.html
│   │   ├── 2024-04/
│   │   │   └── monthly_review.html
│   │   └── client_profile.md
│   └── ...
└── README.md
```

## How to Use

1. For each new client:
   - Create a new folder under `clients/` with their name
   - Copy their profile information to `client_profile.md`
   - Create a folder for the current month (YYYY-MM format)

2. For monthly reviews:
   - Copy `review_template.html` to the client's monthly folder
   - Rename it to `monthly_review.html`
   - Complete during the call
   - Save any additional notes or documents in the same folder

3. Folder Naming Convention:
   - Client folders: `firstname_lastname`
   - Month folders: `YYYY-MM`
   - Review files: `monthly_review.html`

4. Additional Notes:
   - Keep all client-specific documents in their respective folders
   - Maintain chronological order of reviews
   - Update client profile as needed

## Client Profile Template

Each client folder should contain a `client_profile.md` file with:
- Basic Information
- Training History
- Goals
- Medical History
- Equipment Access
- Dietary Preferences
- Contact Information 