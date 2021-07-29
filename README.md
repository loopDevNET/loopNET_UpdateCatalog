# loopNET UpdateCatalog
This package serves the purpose of getting all the information needed for the update of an software developed by us.
The software will check it's existing hash of an update catalog against the one in the repository.
If they match, no catalog update is required. If they don't match, or no hash is set, the software will download the latest version of an update catalog and set the new hash.
