<template>
    <h3 class="mt-10">Red</h3>
    <v-table>
        <thead>
            <tr>
                <th class="text-left">
                    Name
                </th>
                <th class="text-left">
                    Code
                </th>
                <th class="text-left">
                    Sample
                </th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>{{ red50.name }}</td>
                <td>{{ red50.hex }}</td>
                <td>
                    <v-sheet :color="red50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ red100.name }}</td>
                <td>{{ red100.hex }}</td>
                <td>
                    <v-sheet :color="red100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ red200.name }}</td>
                <td>{{ red200.hex }}</td>
                <td>
                    <v-sheet :color="red200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ red300.name }}</td>
                <td>{{ red300.hex }}</td>
                <td>
                    <v-sheet :color="red300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ red400.name }}</td>
                <td>{{ red400.hex }}</td>
                <td>
                    <v-sheet :color="red400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ red500.name }}</td>
                <td>{{ red500.hex }}</td>
                <td>
                    <v-sheet :color="red500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ red600.name }}</td>
                <td>{{ red600.hex }}</td>
                <td>
                    <v-sheet :color="red600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ red700.name }}</td>
                <td>{{ red700.hex }}</td>
                <td>
                    <v-sheet :color="red700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ red800.name }}</td>
                <td>{{ red800.hex }}</td>
                <td>
                    <v-sheet :color="red800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ red900.name }}</td>
                <td>{{ red900.hex }}</td>
                <td>
                    <v-sheet :color="red900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    red50,
    red100,
    red200,
    red300,
    red400,
    red500,
    red600,
    red700,
    red800,
    red900,
} from 'rukkiecodes-colors';
</script>
