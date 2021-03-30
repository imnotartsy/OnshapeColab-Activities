# OnshapeColab-Activities

# Document Settings & Onshape API Keys
Your document settings can be found in your Onshape link:

## Document Settings
The did, wid, eid, and workspace are all unique identifers that are a parts of an Onshape Document's URL.
The example format of this is ```[workspace]/documents/[did]/w/[wid]/e/[wid]```

Ex. `https://cad.onshape.com/documents/f80b668b3ae9c732b3c7d91b/w/cc29213b0eb52b9d3bc554e2/e/b94a0096e0ba6e7f16c2faf1`
- The workspace is the base of the url
  - Ex. `https://cad.onshape.com`
- The `did` is the first 24 character string after "documents"
  - Ex. `f80b668b3ae9c732b3c7d91b`
- The `wid` is the next 24 character string after "/w/"
  - Ex. `cc29213b0eb52b9d3bc554e2`
- The `eid` is the last 24 character string after "/e/"
  - Ex. `b94a0096e0ba6e7f16c2faf1`

## API Keys
To get your API Keys:
1. Sign in to Onshape's [development portal](https://dev-portal.onshape.com/signin)
2. Go to on the API Keys Tab on the left
3. Click "Create New API Key" in the top right
4. Select your Company (if applicable), select your permissions, and click "Create API Key"
5. Copy your access and secret key into a secret place you won't lose them!

## Documentation
Documentation regarding all of the avaliable functions in this playground can be found [here](https://github.com/imnotartsy/OnshapeColab/blob/master/README.md).
