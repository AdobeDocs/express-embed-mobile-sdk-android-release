//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.data.content](../index.md)/[WishesAndGreetingsContentServiceApi](index.md)/[getChildAssetsWithLink](get-child-assets-with-link.md)

# getChildAssetsWithLink

\
suspend fun [getChildAssetsWithLink](get-child-assets-with-link.md)(href: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)): [ContentAssetList](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-asset-list/index.md)

Fetches one ACP asset page from [href](get-child-assets-with-link.md). Callers pass a link from [getInitialAssetsLink](get-initial-assets-link.md) or [getInitialSearchAssetsLink](get-initial-search-assets-link.md) (both already require an ACP link) or an ACP page's `next` link.
