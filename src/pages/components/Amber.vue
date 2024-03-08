<template>
    <h3 class="mt-10">Amber</h3>
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
                <td>{{ amber50.name }}</td>
                <td>{{ amber50.hex }}</td>
                <td>
                    <v-sheet :color="amber50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ amber100.name }}</td>
                <td>{{ amber100.hex }}</td>
                <td>
                    <v-sheet :color="amber100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ amber200.name }}</td>
                <td>{{ amber200.hex }}</td>
                <td>
                    <v-sheet :color="amber200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ amber300.name }}</td>
                <td>{{ amber300.hex }}</td>
                <td>
                    <v-sheet :color="amber300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ amber400.name }}</td>
                <td>{{ amber400.hex }}</td>
                <td>
                    <v-sheet :color="amber400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ amber500.name }}</td>
                <td>{{ amber500.hex }}</td>
                <td>
                    <v-sheet :color="amber500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ amber600.name }}</td>
                <td>{{ amber600.hex }}</td>
                <td>
                    <v-sheet :color="amber600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ amber700.name }}</td>
                <td>{{ amber700.hex }}</td>
                <td>
                    <v-sheet :color="amber700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ amber800.name }}</td>
                <td>{{ amber800.hex }}</td>
                <td>
                    <v-sheet :color="amber800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ amber900.name }}</td>
                <td>{{ amber900.hex }}</td>
                <td>
                    <v-sheet :color="amber900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    amber50,
    amber100,
    amber200,
    amber300,
    amber400,
    amber500,
    amber600,
    amber700,
    amber800,
    amber900,
} from 'rukkiecodes-colors';
</script>
