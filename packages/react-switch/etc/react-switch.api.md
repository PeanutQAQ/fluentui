## API Report File for "@fluentui/react-switch"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { ComponentProps } from '@fluentui/react-utilities';
import { ComponentState } from '@fluentui/react-utilities';
import * as React_2 from 'react';

// @public
export const renderSwitch: (state: SwitchState) => JSX.Element;

// @public
export const Switch: React_2.ForwardRefExoticComponent<SwitchProps & React_2.RefAttributes<HTMLElement>>;

// @public (undocumented)
export interface SwitchCommon extends Omit<React_2.HTMLAttributes<HTMLDivElement>, 'onChange'> {
}

// @public
export interface SwitchProps extends ComponentProps<Partial<SwitchSlots>>, Partial<SwitchCommon> {
}

// @public
export const switchShorthandProps: Array<keyof SwitchSlots>;

// @public
export type SwitchSlots = {};

// @public
export interface SwitchState extends ComponentState<SwitchSlots>, SwitchCommon {
    ref: React_2.Ref<HTMLElement>;
}

// @public
export const useSwitch: (props: SwitchProps, ref: React_2.Ref<HTMLElement>) => SwitchState;

// @public
export const useSwitchStyles: (state: SwitchState) => SwitchState;

// (No @packageDocumentation comment for this package)

```
