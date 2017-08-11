# @gamestdio/scorm

> SCORM 1.2/2004 Wrapper for JavaScript/TypeScript

Integrate your e-learning course with SCORM 1.2/2004 LMS.

This implementation is highly based on a battle tested version from
[pipwerks/scorm-api-wrapper](https://github.com/pipwerks/scorm-api-wrapper).

## Why?

No SCORM wrapper had support for modern JavaScript/TypeScript.

## Usage

```typescript
import { scorm } from "@gamestdio/scorm";

// initialize connection with parent/opener windows
scorm.initialize();

scorm.set('cmi.core.lesson_status', 'Not Attempted');
scorm.commit();

// finish e-learning session
scorm.terminate();
```

## Testing

1. Create a free account on [SCORM Cloud](https://cloud.scorm.com)
2. Download and include one of the [XML Schema Definition files](https://scorm.com/scorm-explained/technical-scorm/content-packaging/xml-schema-definition-files/) into your package.
3. Edit the `imsmanifest.xml` to meet your needs.
4. Upload your e-learning course to SCORM Cloud.

## References

- [SCORM 1.2 Run-Time Environment](http://xml.coverpages.org/SCORM-12-RunTimeEnv.pdf)
- [SCORM 2004 Guide for Programmers](https://www.adlnet.gov/public/uploads/SCORM_Users_Guide_for_Programmers.pdf)
- [Wikipedia: Sharable_Content_Object_Reference_Model](https://en.wikipedia.org/wiki/Sharable_Content_Object_Reference_Model)

## License

MIT
