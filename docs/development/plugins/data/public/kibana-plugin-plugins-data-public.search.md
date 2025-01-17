<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-plugins-data-public](./kibana-plugin-plugins-data-public.md) &gt; [search](./kibana-plugin-plugins-data-public.search.md)

## search variable

<b>Signature:</b>

```typescript
search: {
    aggs: {
        CidrMask: typeof CidrMask;
        dateHistogramInterval: typeof dateHistogramInterval;
        intervalOptions: ({
            display: string;
            val: string;
            enabled(agg: import("../common").IBucketAggConfig): boolean;
        } | {
            display: string;
            val: string;
        })[];
        InvalidEsCalendarIntervalError: typeof InvalidEsCalendarIntervalError;
        InvalidEsIntervalFormatError: typeof InvalidEsIntervalFormatError;
        IpAddress: typeof IpAddress;
        isDateHistogramBucketAggConfig: typeof isDateHistogramBucketAggConfig;
        isNumberType: (agg: import("../common").AggConfig) => boolean;
        isStringType: (agg: import("../common").AggConfig) => boolean;
        isType: (...types: string[]) => (agg: import("../common").AggConfig) => boolean;
        isValidEsInterval: typeof isValidEsInterval;
        isValidInterval: typeof isValidInterval;
        parentPipelineType: string;
        parseEsInterval: typeof parseEsInterval;
        parseInterval: typeof parseInterval;
        propFilter: typeof propFilter;
        siblingPipelineType: string;
        termsAggFilter: string[];
        toAbsoluteDates: typeof toAbsoluteDates;
        boundsDescendingRaw: ({
            bound: number;
            interval: import("moment").Duration;
            boundLabel: string;
            intervalLabel: string;
        } | {
            bound: import("moment").Duration;
            interval: import("moment").Duration;
            boundLabel: string;
            intervalLabel: string;
        })[];
        getNumberHistogramIntervalByDatatableColumn: (column: import("../../expressions").DatatableColumn) => number | undefined;
        getDateHistogramMetaDataByDatatableColumn: (column: import("../../expressions").DatatableColumn, defaults?: Partial<{
            timeZone: string;
        }>) => {
            interval: string | undefined;
            timeZone: string | undefined;
            timeRange: import("../common").TimeRange | undefined;
        } | undefined;
    };
    getResponseInspectorStats: typeof getResponseInspectorStats;
    tabifyAggResponse: typeof tabifyAggResponse;
    tabifyGetColumns: typeof tabifyGetColumns;
}
```
