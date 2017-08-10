# @gamestdio/scorm

> SCORM 1.2/2004 Wrapper for JavaScript/TypeScript

Integrate your e-learning course with SCORM 1.2/2004 LMS.

This implementation is highly based on a battle tested version from
[pipwerks/scorm-api-wrapper](https://github.com/pipwerks/scorm-api-wrapper).

- Require with modern JavaScript/TypeScript
- Works with SCORM 1.2 and 2004

## Why?

No SCORM wrapper had support for modern JavaScript/TypeScript.
## Usage

```typescript
import { scorm } from "@gamestdio/scorm";

scorm.initialize();
scorm.set();
scorm.terminate();
```

## Testing

Create a free account on [SCORM Cloud](https://cloud.scorm.com), and upload your
e-learning course into the platform.

## References

- [SCORM 1.2 Run-Time Environment](http://xml.coverpages.org/SCORM-12-RunTimeEnv.pdf)
- [SCORM 2004 Guide for Programmers](https://www.adlnet.gov/public/uploads/SCORM_Users_Guide_for_Programmers.pdf)
- [Wikipedia: Sharable_Content_Object_Reference_Model](https://en.wikipedia.org/wiki/Sharable_Content_Object_Reference_Model)

## License

MIT
