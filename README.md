# digital-wallet-data-processing-checker
The files that pass through the above checker, are now ready to be discovered. We will convert the file into required format, process the data and insert all the records into mongo db. In case if there is a record that cannot be inserted, then I need to clear that batch of data in all the collections, so that there is no partial discovery (which might cause data mismatch issue).