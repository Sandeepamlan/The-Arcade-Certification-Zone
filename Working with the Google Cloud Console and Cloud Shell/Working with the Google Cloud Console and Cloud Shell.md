
# Working with the Google Cloud Console and Cloud Shell 

# TASK 1
## click Cloud Storage > Bucket and then CREATE  
> Copy PROJECT_ID and Paste on Bucket NAME then CREATE

# TASK 2 & 3
```
gcloud storage buckets create gs://$GOOGLE_CLOUD_PROJECT-2

echo "subscibe to quicklab" > text.txt

gcloud storage cp text.txt gs://$GOOGLE_CLOUD_PROJECT-2
```

### DONE
