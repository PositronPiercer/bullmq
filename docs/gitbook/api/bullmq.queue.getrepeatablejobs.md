<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [Queue](./bullmq.queue.md) &gt; [getRepeatableJobs](./bullmq.queue.getrepeatablejobs.md)

## Queue.getRepeatableJobs() method

Get all repeatable meta jobs.

<b>Signature:</b>

```typescript
getRepeatableJobs(start?: number, end?: number, asc?: boolean): Promise<{
        key: string;
        name: string;
        id: string;
        endDate: number;
        tz: string;
        cron: string;
        next: number;
    }[]>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  start | number | Offset of first job to return. |
|  end | number | Offset of last job to return. |
|  asc | boolean | Determine the order in which jobs are returned based on their next execution time. |

<b>Returns:</b>

Promise&lt;{ key: string; name: string; id: string; endDate: number; tz: string; cron: string; next: number; }\[\]&gt;
