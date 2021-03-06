---
-api-id: M:Windows.Storage.IStorageItemProperties.GetThumbnailAsync(Windows.Storage.FileProperties.ThumbnailMode,System.UInt32)
-api-type: winrt method
---

<!-- Method syntax
public Windows.Foundation.IAsyncOperation<Windows.Storage.FileProperties.StorageItemThumbnail> GetThumbnailAsync(Windows.Storage.FileProperties.ThumbnailMode mode, System.UInt32 requestedSize)
-->

# Windows.Storage.IStorageItemProperties.GetThumbnailAsync

## -description
Retrieves an adjusted thumbnail image for the item, determined by the purpose of the thumbnail and the requested size.

## -parameters
### -param mode
The enum value that describes the purpose of the thumbnail and determines how the thumbnail image is adjusted.

### -param requestedSize
The requested size, in pixels, of the longest edge of the thumbnail. Windows uses the *requestedSize* as a guide and tries to scale the thumbnail image without reducing the quality of the image.

If Windows can't find a thumbnail image that it can scale to meet the requested size, a larger thumbnail might be returned. If no larger thumbnail is available, a thumbnail image that is smaller than the requested size might be returned.

## -returns
When this method completes successfully, it returns a [StorageItemThumbnail](../windows.storage.fileproperties/storageitemthumbnail.md) that represents the thumbnail image or **null** if there is no thumbnail image associated with the item.

## -remarks

## -examples

## -see-also
[GetThumbnailAsync(ThumbnailMode)](istorageitemproperties_getthumbnailasync_1575071988.md), [GetThumbnailAsync(ThumbnailMode, UInt32, ThumbnailOptions)](istorageitemproperties_getthumbnailasync_91362086.md)