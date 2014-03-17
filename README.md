Dexie
=====

Dexie is a local database API for the browser based on indexedDB.
 * Straight forward API, easy to use.
 * Does not hide backend indexedDB from the caller - always possible to reach the backend IDB objects.
 * Portable - works on all modern browsers (IE10+, Chrome, Firefox, Opera 15+, Android browser, Blackberry browser, Opera mobile 16+, Chrome for Android, Firefox for Android, IE Mobile, Safari (with indexedDB shim) and IOS Safari (with indexedDB shim)
 * Well-tested: Thoroughly unit tested
 * Code Completion friendly - Your IDE will guide you as you type.
 * Human readable queries such as: db.friends.where("phone").startsWith("+46").or("country").equals("SE").each(function(){})
 * Promise/A+ compliant
 * Support for case insensitive matching
 * Support for prefix matching
 * Support for matching a set of keys in a single search
 * Support for OR between queries
 * Transaction support
 * Simplified and robust error handling
 * Simplified upgrading framework
 * Built to be easily extended by 3rd part libraries
