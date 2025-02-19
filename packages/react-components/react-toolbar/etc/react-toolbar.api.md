## API Report File for "@fluentui/react-toolbar"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

/// <reference types="react" />

import { ButtonProps } from '@fluentui/react-button';
import { ButtonSlots } from '@fluentui/react-button';
import { ButtonState } from '@fluentui/react-button';
import type { ComponentProps } from '@fluentui/react-utilities';
import type { ComponentState } from '@fluentui/react-utilities';
import { DividerSlots } from '@fluentui/react-divider';
import { DividerState } from '@fluentui/react-divider';
import type { ForwardRefComponent } from '@fluentui/react-utilities';
import * as React_2 from 'react';
import type { Slot } from '@fluentui/react-utilities';
import { SlotClassNames } from '@fluentui/react-utilities';
import { ToggleButtonProps } from '@fluentui/react-button';
import { ToggleButtonState } from '@fluentui/react-button';

// @public
export const renderToolbar_unstable: (state: ToolbarState, contextValues: ToolbarContextValues) => JSX.Element;

// @public
export const renderToolbarGroup_unstable: (state: ToolbarGroupState) => JSX.Element;

// @public
export const Toolbar: ForwardRefComponent<ToolbarProps>;

// @public
export const ToolbarButton: ForwardRefComponent<ToolbarButtonProps>;

// @public
export type ToolbarButtonProps = ComponentProps<ButtonSlots> & Partial<Pick<ButtonProps, 'disabled' | 'disabledFocusable'>> & {
    appearance?: 'primary' | 'subtle';
} & {
    vertical?: boolean;
};

// @public
export type ToolbarButtonState = ComponentState<Partial<ButtonSlots>> & ButtonState & Required<Pick<ToolbarButtonProps, 'vertical'>>;

// @public (undocumented)
export const toolbarClassNames: SlotClassNames<ToolbarSlots>;

// @public (undocumented)
export type ToolbarContextValue = Pick<ToolbarState, 'size' | 'vertical' | 'checkedValues'> & {
    handleToggleButton?: ToggableHandler;
    handleRadio?: ToggableHandler;
};

// @public (undocumented)
export type ToolbarContextValues = {
    toolbar: ToolbarContextValue;
};

// @public
export const ToolbarDivider: ForwardRefComponent<ToolbarDividerProps>;

// @public
export type ToolbarDividerProps = ComponentProps<Partial<DividerSlots>> & {
    vertical?: boolean;
};

// @public
export type ToolbarDividerState = ComponentState<Partial<DividerSlots>> & DividerState;

// @public
export const ToolbarGroup: ForwardRefComponent<ToolbarGroupProps>;

// @public (undocumented)
export const toolbarGroupClassNames: SlotClassNames<ToolbarGroupSlots>;

// @public
export type ToolbarGroupProps = ComponentProps<ToolbarGroupSlots>;

// @public
export type ToolbarGroupState = ComponentState<ToolbarGroupSlots>;

// @public
export type ToolbarProps = ComponentProps<ToolbarSlots> & {
    size?: 'small' | 'medium' | 'large';
    vertical?: boolean;
    checkedValues?: Record<string, string[]>;
    defaultCheckedValues?: Record<string, string[]>;
    onCheckedValueChange?: (e: ToolbarCheckedValueChangeEvent, data: ToolbarCheckedValueChangeData) => void;
};

// @public
export const ToolbarRadioButton: ForwardRefComponent<ToolbarRadioButtonProps>;

// @public
export type ToolbarRadioButtonProps = ComponentProps<ButtonSlots> & Partial<Pick<ToggleButtonProps, 'disabled' | 'disabledFocusable' | 'size'>> & {
    appearance?: 'primary' | 'subtle';
    name: string;
    value: string;
};

// @public
export type ToolbarRadioButtonState = ComponentState<Partial<ButtonSlots>> & ToggleButtonState & Required<Pick<ToggleButtonProps, 'checked'>> & Pick<ToolbarRadioButtonProps, 'name' | 'value'>;

// @public (undocumented)
export type ToolbarSlots = {
    root: Slot<'div'>;
};

// @public
export type ToolbarState = ComponentState<ToolbarSlots> & Required<Pick<ToolbarProps, 'size' | 'checkedValues' | 'vertical'>> & Pick<ToolbarProps, 'defaultCheckedValues' | 'onCheckedValueChange'> & {
    handleToggleButton: ToggableHandler;
    handleRadio: ToggableHandler;
};

// @public
export const ToolbarToggleButton: ForwardRefComponent<ToolbarToggleButtonProps>;

// @public
export type ToolbarToggleButtonProps = ComponentProps<ButtonSlots> & Partial<Pick<ToggleButtonProps, 'disabled' | 'disabledFocusable' | 'size'>> & {
    appearance?: 'primary' | 'subtle';
    name: string;
    value: string;
};

// @public
export type ToolbarToggleButtonState = ComponentState<Partial<ButtonSlots>> & ToggleButtonState & Required<Pick<ToggleButtonProps, 'checked'>> & Pick<ToolbarToggleButtonProps, 'name' | 'value'>;

// @public
export const useToolbar_unstable: (props: ToolbarProps, ref: React_2.Ref<HTMLElement>) => ToolbarState;

// @public
export const useToolbarButton_unstable: (props: ToolbarButtonProps, ref: React_2.Ref<HTMLButtonElement | HTMLAnchorElement>) => ToolbarButtonState;

// @public
export const useToolbarButtonStyles_unstable: (state: ToolbarButtonState) => void;

// @public
export const useToolbarDivider_unstable: (props: ToolbarDividerProps, ref: React_2.Ref<HTMLElement>) => ToolbarDividerState;

// @public
export const useToolbarDividerStyles_unstable: (state: ToolbarDividerState) => ToolbarDividerState;

// @public
export const useToolbarGroup_unstable: (props: ToolbarGroupProps, ref: React_2.Ref<HTMLDivElement>) => ToolbarGroupState;

// @public
export const useToolbarGroupStyles_unstable: (state: ToolbarGroupState) => ToolbarGroupState;

// @public
export const useToolbarRadioButton_unstable: (props: ToolbarRadioButtonProps, ref: React_2.Ref<HTMLButtonElement | HTMLAnchorElement>) => ToolbarRadioButtonState;

// @public
export const useToolbarRadioButtonStyles_unstable: (state: ToolbarRadioButtonState) => void;

// @public
export const useToolbarStyles_unstable: (state: ToolbarState) => ToolbarState;

// @public
export const useToolbarToggleButton_unstable: (props: ToolbarToggleButtonProps, ref: React_2.Ref<HTMLButtonElement | HTMLAnchorElement>) => ToolbarToggleButtonState;

// @public
export const useToolbarToggleButtonStyles_unstable: (state: ToolbarToggleButtonState) => void;

// (No @packageDocumentation comment for this package)

```
