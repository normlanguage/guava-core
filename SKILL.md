# guava.core Skill

Use this skill to work with Norm module `guava.core` version 4. Use only declarations listed below.

## `guava.core`

Source: `ArrayListMultimap.norm`

### `ArrayListMultimap`

```norm
class ArrayListMultimap<K, V> implements ListMultimap<K, V>, Serializable, Multimap<K, V>
```

Type parameters:

- `K`
- `V`

#### `ArrayListMultimap`

```norm
ArrayListMultimap(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `arrayListMultimapCreate`

```norm
ArrayListMultimap<K, V>? arrayListMultimapCreate<K, V>()
```

Type parameters:

- `K`
- `V`

Returns: `ArrayListMultimap<K, V>?`

### `arrayListMultimapCreate`

```norm
ArrayListMultimap<K, V>? arrayListMultimapCreate<K, V>(Integer arg0, Integer arg1)
```

Type parameters:

- `K`
- `V`

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`

Returns: `ArrayListMultimap<K, V>?`

## `guava.core`

Source: `HashCode.norm`

### `HashCode`

```norm
class HashCode
```

#### `HashCode`

```norm
HashCode(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `asInt`

```norm
Integer asInt()
```

Returns: `Integer`

#### `asLong`

```norm
Long asLong()
```

Returns: `Long`

#### `bits`

```norm
Integer bits()
```

Returns: `Integer`

#### `padToLong`

```norm
Long padToLong()
```

Returns: `Long`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

### `hashCodeFromInt`

```norm
HashCode? hashCodeFromInt(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `HashCode?`

### `hashCodeFromLong`

```norm
HashCode? hashCodeFromLong(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `HashCode?`

### `hashCodeFromString`

```norm
HashCode? hashCodeFromString(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `HashCode?`

## `guava.core`

Source: `HashFunction.norm`

### `HashFunction`

```norm
interface HashFunction
```

#### `bits`

```norm
Integer bits()
```

Returns: `Integer`

#### `hashInt`

```norm
HashCode? hashInt(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `HashCode?`

#### `hashLong`

```norm
HashCode? hashLong(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `HashCode?`

#### `hashUnencodedChars`

```norm
HashCode? hashUnencodedChars(CharSequence? arg0)
```

Parameters:

- `arg0`: `CharSequence?`

Returns: `HashCode?`

## `guava.core`

Source: `Hashing.norm`

### `Hashing`

```norm
class Hashing
```

#### `Hashing`

```norm
Hashing(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `hashingConsistentHash`

```norm
Integer hashingConsistentHash(Long arg0, Integer arg1)
```

Parameters:

- `arg0`: `Long`
- `arg1`: `Integer`

Returns: `Integer`

### `hashingGoodFastHash`

```norm
HashFunction? hashingGoodFastHash(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `HashFunction?`

### `hashingMurmur3_128`

```norm
HashFunction? hashingMurmur3_128()
```

Returns: `HashFunction?`

### `hashingSha256`

```norm
HashFunction? hashingSha256()
```

Returns: `HashFunction?`

### `hashingSha512`

```norm
HashFunction? hashingSha512()
```

Returns: `HashFunction?`

## `guava.core`

Source: `ImmutableList.norm`

### `ImmutableList`

```norm
class ImmutableList<E> extends ImmutableCollection<E> implements JavaList<E>, RandomAccess, Serializable, Collection<E>
```

Type parameters:

- `E`

#### `ImmutableList`

```norm
ImmutableList(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `contains`

```norm
Boolean contains(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `indexOf`

```norm
Integer indexOf(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Integer`

#### `lastIndexOf`

```norm
Integer lastIndexOf(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Integer`

#### `reverse`

```norm
ImmutableList<E>? reverse()
```

Returns: `ImmutableList<E>?`

#### `subList`

```norm
ImmutableList<E>? subList(Integer arg0, Integer arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`

Returns: `ImmutableList<E>?`

### `immutableListOf`

```norm
ImmutableList<E>? immutableListOf<E>()
```

Type parameters:

- `E`

Returns: `ImmutableList<E>?`

### `immutableListOf`

```norm
ImmutableList<E>? immutableListOf<E>(E? arg0)
```

Type parameters:

- `E`

Parameters:

- `arg0`: `E?`

Returns: `ImmutableList<E>?`

### `immutableListOf`

```norm
ImmutableList<E>? immutableListOf<E>(E? arg0, E? arg1)
```

Type parameters:

- `E`

Parameters:

- `arg0`: `E?`
- `arg1`: `E?`

Returns: `ImmutableList<E>?`

### `immutableListOf`

```norm
ImmutableList<E>? immutableListOf<E>(E? arg0, E? arg1, E? arg2)
```

Type parameters:

- `E`

Parameters:

- `arg0`: `E?`
- `arg1`: `E?`
- `arg2`: `E?`

Returns: `ImmutableList<E>?`

### `immutableListOf`

```norm
ImmutableList<E>? immutableListOf<E>(E? arg0, E? arg1, E? arg2, E? arg3)
```

Type parameters:

- `E`

Parameters:

- `arg0`: `E?`
- `arg1`: `E?`
- `arg2`: `E?`
- `arg3`: `E?`

Returns: `ImmutableList<E>?`

## `guava.core`

Source: `ImmutableMap.norm`

### `ImmutableMap`

```norm
class ImmutableMap<K, V> implements JavaMap<K, V>, Serializable
```

Type parameters:

- `K`
- `V`

#### `ImmutableMap`

```norm
ImmutableMap(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `containsKey`

```norm
Boolean containsKey(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `containsValue`

```norm
Boolean containsValue(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `get`

```norm
V? get(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `V?`

#### `getOrDefault`

```norm
V? getOrDefault(Any? arg0, V? arg1)
```

Parameters:

- `arg0`: `Any?`
- `arg1`: `V?`

Returns: `V?`

#### `isEmpty`

```norm
Boolean isEmpty()
```

Returns: `Boolean`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

### `immutableMapOf`

```norm
ImmutableMap<K, V>? immutableMapOf<K, V>()
```

Type parameters:

- `K`
- `V`

Returns: `ImmutableMap<K, V>?`

### `immutableMapOf`

```norm
ImmutableMap<K, V>? immutableMapOf<K, V>(K? arg0, V? arg1)
```

Type parameters:

- `K`
- `V`

Parameters:

- `arg0`: `K?`
- `arg1`: `V?`

Returns: `ImmutableMap<K, V>?`

### `immutableMapOf`

```norm
ImmutableMap<K, V>? immutableMapOf<K, V>(K? arg0, V? arg1, K? arg2, V? arg3)
```

Type parameters:

- `K`
- `V`

Parameters:

- `arg0`: `K?`
- `arg1`: `V?`
- `arg2`: `K?`
- `arg3`: `V?`

Returns: `ImmutableMap<K, V>?`

### `immutableMapOf`

```norm
ImmutableMap<K, V>? immutableMapOf<K, V>(K? arg0, V? arg1, K? arg2, V? arg3, K? arg4, V? arg5)
```

Type parameters:

- `K`
- `V`

Parameters:

- `arg0`: `K?`
- `arg1`: `V?`
- `arg2`: `K?`
- `arg3`: `V?`
- `arg4`: `K?`
- `arg5`: `V?`

Returns: `ImmutableMap<K, V>?`

## `guava.core`

Source: `ImmutableSet.norm`

### `ImmutableSet`

```norm
class ImmutableSet<E> extends ImmutableCollection<E> implements JavaSet<E>, Serializable, Collection<E>
```

Type parameters:

- `E`

#### `ImmutableSet`

```norm
ImmutableSet(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `contains`

```norm
Boolean contains(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

### `immutableSetOf`

```norm
ImmutableSet<E>? immutableSetOf<E>()
```

Type parameters:

- `E`

Returns: `ImmutableSet<E>?`

### `immutableSetOf`

```norm
ImmutableSet<E>? immutableSetOf<E>(E? arg0)
```

Type parameters:

- `E`

Parameters:

- `arg0`: `E?`

Returns: `ImmutableSet<E>?`

### `immutableSetOf`

```norm
ImmutableSet<E>? immutableSetOf<E>(E? arg0, E? arg1)
```

Type parameters:

- `E`

Parameters:

- `arg0`: `E?`
- `arg1`: `E?`

Returns: `ImmutableSet<E>?`

### `immutableSetOf`

```norm
ImmutableSet<E>? immutableSetOf<E>(E? arg0, E? arg1, E? arg2)
```

Type parameters:

- `E`

Parameters:

- `arg0`: `E?`
- `arg1`: `E?`
- `arg2`: `E?`

Returns: `ImmutableSet<E>?`

### `immutableSetOf`

```norm
ImmutableSet<E>? immutableSetOf<E>(E? arg0, E? arg1, E? arg2, E? arg3)
```

Type parameters:

- `E`

Parameters:

- `arg0`: `E?`
- `arg1`: `E?`
- `arg2`: `E?`
- `arg3`: `E?`

Returns: `ImmutableSet<E>?`

## `guava.core`

Source: `Joiner.norm`

### `Joiner`

```norm
class Joiner
```

#### `Joiner`

```norm
Joiner(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `join`

```norm
String? join(Function<Iterator<Any>?()>? arg0)
```

Parameters:

- `arg0`: `Function<Iterator<Any>?()>?`

Returns: `String?`

#### `skipNulls`

```norm
Joiner? skipNulls()
```

Returns: `Joiner?`

#### `useForNull`

```norm
Joiner? useForNull(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Joiner?`

### `joinerOn`

```norm
Joiner? joinerOn(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Joiner?`

## `guava.core`

Source: `Multimap.norm`

### `Multimap`

```norm
interface Multimap<K, V>
```

Type parameters:

- `K`
- `V`

#### `clear`

```norm
Void clear()
```

Returns: `Void`

#### `containsEntry`

```norm
Boolean containsEntry(Any? arg0, Any? arg1)
```

Parameters:

- `arg0`: `Any?`
- `arg1`: `Any?`

Returns: `Boolean`

#### `containsKey`

```norm
Boolean containsKey(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `containsValue`

```norm
Boolean containsValue(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `get`

```norm
Collection<V>? get(K? arg0)
```

Parameters:

- `arg0`: `K?`

Returns: `Collection<V>?`

#### `isEmpty`

```norm
Boolean isEmpty()
```

Returns: `Boolean`

#### `keySet`

```norm
JavaSet<K>? keySet()
```

Returns: `JavaSet<K>?`

#### `put`

```norm
Boolean put(K? arg0, V? arg1)
```

Parameters:

- `arg0`: `K?`
- `arg1`: `V?`

Returns: `Boolean`

#### `remove`

```norm
Boolean remove(Any? arg0, Any? arg1)
```

Parameters:

- `arg0`: `Any?`
- `arg1`: `Any?`

Returns: `Boolean`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `values`

```norm
Collection<V>? values()
```

Returns: `Collection<V>?`

## `guava.core`

Source: `Preconditions.norm`

### `Preconditions`

```norm
class Preconditions
```

#### `Preconditions`

```norm
Preconditions(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `preconditionsCheckArgument`

```norm
Void preconditionsCheckArgument(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Void`

### `preconditionsCheckElementIndex`

```norm
Integer preconditionsCheckElementIndex(Integer arg0, Integer arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`

Returns: `Integer`

### `preconditionsCheckNotNull`

```norm
T? preconditionsCheckNotNull<T>(T? arg0)
```

Type parameters:

- `T`

Parameters:

- `arg0`: `T?`

Returns: `T?`

### `preconditionsCheckPositionIndex`

```norm
Integer preconditionsCheckPositionIndex(Integer arg0, Integer arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`

Returns: `Integer`

### `preconditionsCheckPositionIndexes`

```norm
Void preconditionsCheckPositionIndexes(Integer arg0, Integer arg1, Integer arg2)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`
- `arg2`: `Integer`

Returns: `Void`

### `preconditionsCheckState`

```norm
Void preconditionsCheckState(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Void`

## `guava.core`

Source: `Splitter.norm`

### `Splitter`

```norm
class Splitter
```

#### `Splitter`

```norm
Splitter(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `limit`

```norm
Splitter? limit(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Splitter?`

#### `omitEmptyStrings`

```norm
Splitter? omitEmptyStrings()
```

Returns: `Splitter?`

#### `split`

```norm
Iterable<String>? split(CharSequence? arg0)
```

Parameters:

- `arg0`: `CharSequence?`

Returns: `Iterable<String>?`

#### `splitToList`

```norm
JavaList<String>? splitToList(CharSequence? arg0)
```

Parameters:

- `arg0`: `CharSequence?`

Returns: `JavaList<String>?`

#### `trimResults`

```norm
Splitter? trimResults()
```

Returns: `Splitter?`

### `splitterFixedLength`

```norm
Splitter? splitterFixedLength(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Splitter?`

### `splitterOn`

```norm
Splitter? splitterOn(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Splitter?`

### `splitterOnPattern`

```norm
Splitter? splitterOnPattern(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Splitter?`

## `guava.core`

Source: `Strings.norm`

### `Strings`

```norm
class Strings
```

#### `Strings`

```norm
Strings(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `stringsCommonPrefix`

```norm
String? stringsCommonPrefix(CharSequence? arg0, CharSequence? arg1)
```

Parameters:

- `arg0`: `CharSequence?`
- `arg1`: `CharSequence?`

Returns: `String?`

### `stringsCommonSuffix`

```norm
String? stringsCommonSuffix(CharSequence? arg0, CharSequence? arg1)
```

Parameters:

- `arg0`: `CharSequence?`
- `arg1`: `CharSequence?`

Returns: `String?`

### `stringsEmptyToNull`

```norm
String? stringsEmptyToNull(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `stringsIsNullOrEmpty`

```norm
Boolean stringsIsNullOrEmpty(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Boolean`

### `stringsNullToEmpty`

```norm
String? stringsNullToEmpty(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `stringsPadEnd`

```norm
String? stringsPadEnd(String? arg0, Integer arg1, CodePoint arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`
- `arg2`: `CodePoint`

Returns: `String?`

### `stringsPadStart`

```norm
String? stringsPadStart(String? arg0, Integer arg1, CodePoint arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`
- `arg2`: `CodePoint`

Returns: `String?`

### `stringsRepeat`

```norm
String? stringsRepeat(String? arg0, Integer arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`

Returns: `String?`

## `guava.core.collect`

Source: `collect/ImmutableCollection.norm`

### `ImmutableCollection`

```norm
class ImmutableCollection<E> extends AbstractCollection<E> implements Serializable, Collection<E>
```

Type parameters:

- `E`

#### `ImmutableCollection`

```norm
ImmutableCollection(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `guava.core.collect`

Source: `collect/ListMultimap.norm`

### `ListMultimap`

```norm
interface ListMultimap<K, V> extends Multimap<K, V>
```

Type parameters:

- `K`
- `V`

