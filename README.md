An npm package for getting photo urls from html file inputs

## Install
`npm i -s get-photo-url`

## Example
```
<-- html -->
<input type="file" name="photo" id="addPhotoInput" />
```
```
// javascript
import getPhotoUrl from 'get-photo-url'

const addPhoto = async () => {
  const photoUrl = await getPhotoUrl('#addPhotoInput')
  // do something with photoUrl
}
```
