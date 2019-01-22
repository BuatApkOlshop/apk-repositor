steps:
- name: 'gcr.io/cloud-builders/go'
  args: ['install', '.']
  env: ['PROJECT_ROOT=BuatApkOlahop']
- name: 'gcr.io/cloud-builders/go'
  args: ['build', 'BuatApkOlshop']
  env: ['PROJECT_ROOT=BuatApkOlshop']
artifacts:
  objects:
    location: 'gs://$PROJECT_ID/'
    paths: ['BuatApkOlshop']
